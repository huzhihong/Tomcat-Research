Tomcat-Research
==================

本项最开始来自于https://github.com/codefollower/Tomcat-Research.git，本人准备在其基础上阅读tomcat源码并做相应的注释，启动本项目可以直接使用idea，运行配置参数如下：

```
<configuration default="false" name="tomcat" type="Application" factoryName="Application">
  <extension name="coverage" enabled="false" merge="false" sample_coverage="true" runner="idea" />
  <option name="MAIN_CLASS_NAME" value="org.apache.catalina.startup.Bootstrap" />
  <option name="VM_PARAMETERS" value="-Dcatalina.home=launch -Dcatalina.base=launch -Djava.endorsed.dirs=launch/endorsed -Djava.io.tmpdir=launch/temp -Djava.util.logging.manager=org.apache.juli.ClassLoaderLogManager -Djava.util.logging.config.file=launch/conf/logging.properties" />
  <option name="PROGRAM_PARAMETERS" value="start" />
  <option name="WORKING_DIRECTORY" value="file://$PROJECT_DIR$" />
  <option name="ALTERNATIVE_JRE_PATH_ENABLED" value="true" />
  <option name="ALTERNATIVE_JRE_PATH" value="jdk8" />
  <option name="ENABLE_SWING_INSPECTOR" value="false" />
  <option name="ENV_VARIABLES" />
  <option name="PASS_PARENT_ENVS" value="true" />
  <module name="tomcat-research" />
  <envs />
  <method />
</configuration>
```