or = $1$2
or2 = $(if $1$2, T)
and = $(if $1, $(if $2, T))
not = $(if $1,,T)
nand = $(call not,$(call and,$1,$2)) nor = $(call not,$(call or,$1,$2))
xor = $(call and,$(call or,$1,$2),$(call not,$(call and,$1,$2)))

# or :
# nand = $(if $1,$(if $2,,T),T)
# nor = $(if $1$2,,T)
# xor = $(if $1,$(if $2,,T),$(if $2,T))

$(info $(call or,,ali))		 # (false || true)
$(info $(call or,,))		 # (false || false)
$(info $(call or,mahdi,))	 # (true  || false)
$(info $(call or,mahdi,ali)) # (true  || true)