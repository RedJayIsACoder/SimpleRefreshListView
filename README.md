#SimpleRefreshListView<br/>
How To Use:<br/>
  1.在项目的build.gradle文件下添加以下代码:<br/>
    <p>
      	allprojects {
		repositories {
			...
			maven { url 'https://www.jitpack.io' }
		}
	}
    <p/><br/><br/><br/>
  2.在module的build.gradle文件下添加以下代码:<br/>
          	dependencies {
	        compile 'com.github.HeIsHero:SimpleRefreshListView:1.3.0'
              }
