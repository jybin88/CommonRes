# commonRes
## 使用步骤

### 1. 在project的build.gradle添加如下代码(如下图)

	allprojects {
	    repositories {
	        ...
	        maven { url "https://jitpack.io" }
	    }
	}

![](<https://github.com/jybin88/public/raw/master/dependence.png>)


### 2. 在Module的build.gradle添加依赖

    compile 'com.github.jybin88:CommonRes:V0.1'
