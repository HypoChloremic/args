# args
Python argparse cheatsheet
`	import argparse
	parser = argparse.ArgumentParser()
	parser.add_argument('--version', action='version', version='%(prog)s 2.0')
	parser.set_defaults(arg=value)
	args = parser.parse_args()`
