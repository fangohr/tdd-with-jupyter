test: test_foo.py foo.py
	py.test -v test_foo.py

test_foo.py: test_foo.ipynb
	jupyter nbconvert test_foo.ipynb --to python

foo.py: foo.ipynb
	jupyter nbconvert foo.ipynb --to python

clean:
	rm -f test_foo.py foo.py
