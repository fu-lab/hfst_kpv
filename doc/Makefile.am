## Process this file with automake to produce Makefile.in
## Copyright: Sámediggi/Divvun/UiT
## Licence: GPL v3+

# List all jspwiki files that should be created from source files in the
# JSP_PAGES variable. The filename pattern is as follows:
#
# dir/filename.lexc => filename-dir.jspwiki

if CAN_DOCC

JSP_PAGES=root-morphology.jspwiki  \
		  adjectives-affixes.jspwiki       \
		  nouns-affixes.jspwiki            \
		  pronouns-affixes.jspwiki           \
		  propernouns-affixes.jspwiki      \
		  verbs-affixes.jspwiki \
		  kpv-phon-phonology.jspwiki 
# clitics-morphology.jspwiki       \
# compounding-morphology.jspwiki   \
# abbreviations-stems.jspwiki      \
# acronyms-stems.jspwiki           \
# adjectives-oahpa-stems.jspwiki   \
# adjectives-stems.jspwiki         \
# adpositions-stems.jspwiki        \
# adverbs-stems.jspwiki            \
# conjunctions-stems.jspwiki       \
# interjections-stems.jspwiki      \
# nouns-oahpa-stems.jspwiki        \
# nouns-stems.jspwiki              \
# numerals-stems.jspwiki           \
# particles-stems.jspwiki          \
# pronouns-stems.jspwiki           \
# propernouns-stems.jspwiki        \
# punctuation-stems.jspwiki        \
# smi-propernouns-stems.jspwiki    \
# subjunctions-stems.jspwiki       \
# verbs-stems.jspwiki              \
# adjectives-oahpa-affixes.jspwiki \
ALLINONE_JSP_PAGE=$(srcdir)/$(GTLANG).jspwiki

LINKS=$(srcdir)/Links.jspwiki

endif # CAN_DOCC

include $(top_srcdir)/am-shared/doc-dir-include.am
