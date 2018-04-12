# ./gradlew clean build --parallel

1. Kotlin JVM + Gradle 4.0: independent projects are executed in parallel as expected
https://scans.gradle.com/s/mi4yt37vhr6da
2. Kotlin JVM + Gradle 4.6: no parallel execution for Kotlin in independent projects
https://scans.gradle.com/s/rs2j4265q4xy4
3. Kotlin JS + Gradle 4.6: independent projects are executed in parallel as expected
https://gradle.com/s/pb3mqbqilrngm
