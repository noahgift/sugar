setup:
	python3 -m venv ~/.sugar
	source ~/.sugar/bin/activate

makesite:
	jupyter-book create ../TEMPLATE/sugar

buildsite:
	jupyter-book build ../TEMPLATE/sugar
	cp -R ../TEMPLATE/sugar/* ../
install:
	pip install --upgrade pip &&\
		pip install -r requirements.txt
