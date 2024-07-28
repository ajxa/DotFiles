setHook("rstudio.sessionInit", function(newSession) {
  cat(R.version$version.string)
  cat("\n")
  cat("Library Path:", .libPaths()[1], sep = "\n\t")
  
  
},action = "replace")

options(styler.addins_style_transformer = "grkstyle::grk_style_transformer()")

