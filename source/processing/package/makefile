
all: bin/iif_process.py iif_processor/__init__.py iif_processor/generate_json.py

bin/iif_process.py: ../process.py
	cp ../process.py bin/iif_process.py

iif_processor/__init__.py: ../__init__.py
	cp ../__init__.py iif_processor

iif_processor/generate_json.py: ../generate_json.py
	cp ../generate_json.py iif_processor
