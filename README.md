
# Reproduce Issue

1. Open project (as imported Gradle project).
1. Open `buildSrc/src/main/java/example/Test.java`
1. Select `"abc"`, perform variable extraction refactoring (ctrl-alt-v).
1. Observe that `abc` variable is created but usage is not replaced (and no opportunity to rename the variable is provided).
