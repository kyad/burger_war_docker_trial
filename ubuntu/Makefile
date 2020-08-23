.PHONY: build
build:
	docker build -t ai-robocon-container-trial:0.1.0 .

.PHONY: save
save:
	docker save ai-robocon-container-trial:0.1.0 -o ai-robocon-container-trial-0.1.0.tar

.PHONY: load
load:
	docker image load -i ai-robocon-container-trial-0.1.0.tar
