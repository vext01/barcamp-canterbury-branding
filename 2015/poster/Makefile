.PHONY: all
all: poster.pdf poster.png

.SUFFIXES:      .svg .pdf .png
.svg.pdf:
	inkscape --export-pdf=$@ $<

.svg.png:
	inkscape --export-png=$@ $<
