# Superuser
修改build.gradle如下
buildscript {
  repositories {
        google()
        jcenter()
     // mavenCentral()
     }
       dependencies {
       classpath "com.android.tools.build:gradle:4.0.1"
    }
    }
     allprojects {
       repositories {
       jcenter()
       google()
      }
     }
