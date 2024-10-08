- Least privilege principle:
	- container should have minimum permissions necessary to perform their intended functions.
	- run container as non-root user whenever possible.
	- avoid running privileged containers, which have access to all the host's resources.
- Read Only file system
	- use the `--read-only` flag when starting your containers to make their file-systems read-only.
	- implement volume mounts or `tmpfs` mounts for locations that require write access.
- Resource Isolation
	- User Docker build-in resource constraints to limit the resources your containers can consume.
	- Use network segmentation and firewalls to isolate your containers and limit their communication.
- Audit Logs
	- capture container logs, outputting them to a centralized logging solution.
	- implement log analysis tools to monitor for suspicious activity and automatically alert if a potential incident is detected.