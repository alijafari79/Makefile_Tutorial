# If your make version is greater than or equal 
# to the need, then  "ok" will be the version !
# Otherwise will be empty !

need := 3.80
ok := $(filter $(need),$(firstword $(sort $(MAKE_VERSION) $(need))))

all: ; @echo $(ok)
