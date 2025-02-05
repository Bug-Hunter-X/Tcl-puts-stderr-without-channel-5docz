# Tcl puts stderr without channel

This repository demonstrates a common error in Tcl: using `puts stderr` without explicitly specifying the channel. This will cause the script to fail silently and unexpectedly. The solution shows how to correct this by using the `stderr` channel directly.