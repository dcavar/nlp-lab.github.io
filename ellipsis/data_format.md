# The Hoosier Ellipsis Corpus - Data Format

Created: [Damir Cavar], 2023-06-07

Last change: [Damir Cavar], 2024-03-20


## Types of Ellipsis

We collect data covering the following ellipsis types:

- Gapping
- Stripping
- Verb phrase ellipsis
- Pseudogapping
- Answer ellipsis
- Sluicing
- Nominal ellipsis
- Comparative deletion
- Null complement anaphora


## Data Format

The data format is based on plain Unicode text. The general data structure in the files is:

	# comments and meta-data
	# 

	EXAMPLE WITH ELLIPSIS INDICATED ELIDED LOCATION USING 3 UNDERSCORES
	----
	EXAMPLE WITH ELLIPSIS UNDONE
	# comments and meta-data

	EXAMPLE WITH ELLIPSIS INDICATED ELIDED LOCATION USING 3 UNDERSCORES
	----
	EXAMPLE WITH ELLIPSIS UNDONE
	# comments and meta-data

There can be numerous meta-data lines that start with a `#`.

Between the initial meta-data and the first example is at least one empty line.

The location of elided words or phrases is indicated by 3 underline characters.

Between the sentence with ellipsis and the same sentence with ellipsis undone is a seperator of 4 dashes.


That is:
- the target sentence containing elided elements is preceded by at least one empty line
- a sparation line with 4 dashes splits it from the full-form sentence without ellipsis

In addition, context preceding or following the ellipsis construction can be added to the example, indicated with `B:` for "before" and with `A:` for "after" context. The before and after lines should be in the same order as the lines in the narrative or context where the ellipsis construction is found. See the example below. The context can be specified immediately after the ellipsis construction or after the full-form sentence without ellipsis as in the two example below.

Example 1:

	# GENERAL META

	John reads a book and Mary ___ a newspaper.
	B: I came home.
	B: I saw John in the living room.
	B: I saw Mary in the kitchen.
	A: I am going to a bar.
	----
	John reads a book and Mary reads a newspaper.
	# EXAMPLE SPECIFIC META DATA

Example 2:

	# GENERAL META

	John reads a book and Mary ___ a newspaper.
	----
	John reads a book and Mary reads a newspaper.
	B: I came home.
	B: I saw John in the living room.
	B: I saw Mary in the kitchen.
	A: I am going to a bar.
	# EXAMPLE SPECIFIC META DATA



(C) 2023-2024 by [Damir Cavar], NLP-Lab


[Damir Cavar]: http://damir.cavar.me/ "Damir Cavar"
