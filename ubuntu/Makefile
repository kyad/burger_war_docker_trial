TAG=0.1.1

.PHONY: build
build:
	docker build -t ai-robocon-container-trial:$(TAG) .

.PHONY: save
save:
	docker save ai-robocon-container-trial:$(TAG) -o ai-robocon-container-trial-$(TAG).tar

.PHONY: load
load:
	docker image load -i ai-robocon-container-trial-$(TAG).tar
