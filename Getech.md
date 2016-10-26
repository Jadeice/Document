# Getech #
## 1. [Butterknife](http://jakewharton.github.io/butterknife/) ##

#### 版本8.*以后的使用方法 ####

- Project build.gradle

		buildscript {
		    repositories {
		        jcenter()
		    }
		    dependencies {
		        classpath 'com.android.tools.build:gradle:2.2.2'
				// 添加此项
		        classpath 'com.neenbedankt.gradle.plugins:android-apt:1.8'
		
		        // NOTE: Do not place your application dependencies here; they belong
		        // in the individual module build.gradle files
		    }
		}	

- Module build.gradle

		apply plugin: 'com.android.application'
		// 添加此项
		apply plugin: 'com.neenbedankt.android-apt'
		......
		dependencies {
			......
			// 添加如下
		    compile 'com.jakewharton:butterknife:8.4.0'
		    apt 'com.jakewharton:butterknife-compiler:8.4.0'
		}


## 2.  ##
> 哈哈
> 哈哈

