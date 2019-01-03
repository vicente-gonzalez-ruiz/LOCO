include $(HOME)/Makefile_templates/tex2eps_rule/Makefile
include $(HOME)/Makefile_templates/fig2eps_rule/Makefile
include $(HOME)/Makefile_templates/eps2pdf_rule/Makefile
include $(HOME)/Makefile_templates/pdf2png_rule/Makefile
include $(HOME)/Makefile_templates/pdf2svg_rule/Makefile

default:	all

all:	$(TMPs)

# Original files
FIGs := $(wildcard *.fig)

# Temporal files
TMPs += $(FIGs:%.fig=%.eps)
TMPs += $(FIGs:%.fig=%.svg)
