Run `./gradlew resolveDetached --stacktrace`.

Shouldn't it produce identical results to `./gradlew resolveAttached --stacktrace`?

Note that this is only a problem with the root project; resolving a subproject in a detached configuration works fine; run `./gradlew resolveDetachedSubproject --stacktrace` to see.
