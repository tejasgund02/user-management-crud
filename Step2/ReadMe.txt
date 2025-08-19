Pipeline Stages

build: Docker multi-stage build for backend + frontend

test: Run lint/unit tests

deploy: SSH into VM or use Docker context for deployment


Security:

Use GitLab masked variables for SSH keys & registry credentials

Limit runner access with tags

Pull images over HTTPS from private registry