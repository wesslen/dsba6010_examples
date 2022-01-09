setwd("/workspace/dsba6010_examples")
setHook("rstudio.sessionInit", function(newSession) {
  if (newSession && is.null(rstudioapi::getActiveProject()))
    rstudioapi::openProject("/workspace/dsba6010_examples/")
}, action = "append")

