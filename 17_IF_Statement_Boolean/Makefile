# Two Types of if statement using $(if) or ifdef

# Pay Attention : "echo" is a shell command and can't be used in ifdef statement !
# Use $(info) instead to log sth ;

EMPTY =
FULL = "ALI"

############\\ IFDEF //##############
ifdef EMPTY
$(info ifdef->Is Full)
else
$(info ifdef->Is Empty)
endif
####################
ifdef FULL
$(info ifdef->Is Full)
else
$(info ifdef->Is Empty)
endif
######################################

############\\ IF //##################

all: empty full

empty:
	$(if $(EMPTY), @echo "Is Full", @echo "Is Empty")

########################

full:
	$(if $(FULL), @echo "Is Full", @echo "Is Empty")

######################################