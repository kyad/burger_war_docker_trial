VERSION=0.2.0

.PHONY: build
build:
	docker build -t ai-robocon-container-trial:$(VERSION) .

.PHONY: save
save:
	docker save ai-robocon-container-trial:$(VERSION) -o ai-robocon-container-trial-$(VERSION).tar

.PHONY: load
load:
	docker image load -i ai-robocon-container-trial-$(VERSION).tar
