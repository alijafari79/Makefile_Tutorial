# GNU make treats any non-empty string as true. But if you work with truth
# values and $(if) a lot, it can be helpful to use just one consistent value for
# true. The following make-truth function turns any non-empty string into the
# value T :

# make-truth = $(if $1, T, F)
# or :
# make-truth = $(if $1, T)

make-truth = $(if $1, T, F)


# Call the function above using $(call) :
$(info $(call make-truth,))
$(info $(call make-truth,true))
$(info $(call make-truth,a b c))