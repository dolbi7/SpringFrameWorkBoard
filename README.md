# SpringFrameWorkBoard



//// Spring Frame git 명령어

aaa@DESKTOP-IQ2JT8K MINGW64 ~/git/BoardMaria/BoardMaria (master)
$ git init
Initialized empty Git repository in C:/Users/aaa/git/BoardMaria/BoardMaria/.git/


aaa@DESKTOP-IQ2JT8K MINGW64 ~/git/BoardMaria/BoardMaria (master)
$ git remote add origin https://github.com/dolbi7/BoardMaria.git

aaa@DESKTOP-IQ2JT8K MINGW64 ~/git/BoardMaria/BoardMaria (master)
$ git add .
warning: in the working copy of '.project', LF will be replaced by CRLF the next
 time Git touches it
warning: in the working copy of '.settings/org.eclipse.jdt.core.prefs', LF will
be replaced by CRLF the next time Git touches it
warning: in the working copy of '.settings/org.eclipse.m2e.core.prefs', LF will
be replaced by CRLF the next time Git touches it
warning: in the working copy of '.settings/org.eclipse.wst.validation.prefs', LF
 will be replaced by CRLF the next time Git touches it
warning: in the working copy of '.settings/org.springframework.ide.eclipse.beans
.core.prefs', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of '.settings/org.springframework.ide.eclipse.core.
prefs', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of '.springBeans', LF will be replaced by CRLF the
next time Git touches it
warning: in the working copy of 'pom.xml', LF will be replaced by CRLF the next
time Git touches it
warning: in the working copy of 'src/main/resources/log4j.xml', LF will be repla
ced by CRLF the next time Git touches it
warning: in the working copy of 'src/main/webapp/WEB-INF/spring/appServlet/servl
et-context.xml', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'src/main/webapp/WEB-INF/spring/root-context.xml
', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'src/main/webapp/WEB-INF/views/home.jsp', LF wil
l be replaced by CRLF the next time Git touches it
warning: in the working copy of 'src/main/webapp/WEB-INF/web.xml', LF will be re
placed by CRLF the next time Git touches it
warning: in the working copy of 'src/test/resources/log4j.xml', LF will be repla
ced by CRLF the next time Git touches it
warning: in the working copy of 'target/classes/log4j.xml', LF will be replaced
by CRLF the next time Git touches it
warning: in the working copy of 'target/m2e-wtp/web-resources/META-INF/maven/com
.BoardMaria/controller/pom.xml', LF will be replaced by CRLF the next time Git t
ouches it
warning: in the working copy of 'target/m2e-wtp/web-resources/META-INF/maven/com
.SFTest/controller/pom.xml', LF will be replaced by CRLF the next time Git touch
es it
warning: in the working copy of 'target/test-classes/log4j.xml', LF will be repl
aced by CRLF the next time Git touches it
warning: in the working copy of 'workspace-sts-3.9.14.RELEASE/BoardMaria/target/
m2e-wtp/web-resources/META-INF/maven/com.BoardMaria/controller/pom.xml', LF will
 be replaced by CRLF the next time Git touches it

aaa@DESKTOP-IQ2JT8K MINGW64 ~/git/BoardMaria/BoardMaria (master)
$ git commit -m "boardmaria"
[master (root-commit) a65d206] boardmaria
 114 files changed, 9226 insertions(+)
 create mode 100644 .classpath
 create mode 100644 .project
 create mode 100644 .settings/org.eclipse.jdt.core.prefs
 create mode 100644 .settings/org.eclipse.m2e.core.prefs
 create mode 100644 .settings/org.eclipse.wst.common.component
 create mode 100644 .settings/org.eclipse.wst.common.project.facet.core.xml
 create mode 100644 .settings/org.eclipse.wst.validation.prefs
 create mode 100644 .settings/org.springframework.ide.eclipse.beans.core.prefs
 create mode 100644 .settings/org.springframework.ide.eclipse.core.prefs
 create mode 100644 .springBeans
 create mode 100644 pom.xml
 create mode 100644 src/main/java/com/BoardMaria/controller/BoardController.java

 create mode 100644 src/main/java/com/BoardMaria/controller/BoardRestController.
java
 create mode 100644 src/main/java/com/BoardMaria/controller/MasterController.jav
a
 create mode 100644 src/main/java/com/BoardMaria/controller/StudyController.java

 create mode 100644 src/main/java/com/BoardMaria/controller/UserController.java
 create mode 100644 src/main/java/com/BoardMaria/dao/BoardDAO.java
 create mode 100644 src/main/java/com/BoardMaria/dao/BoardDAOImpl.java
 create mode 100644 src/main/java/com/BoardMaria/dao/MasterDAO.java
 create mode 100644 src/main/java/com/BoardMaria/dao/MasterDAOImpl.java
 create mode 100644 src/main/java/com/BoardMaria/dao/UserDAO.java
 create mode 100644 src/main/java/com/BoardMaria/dao/UserDAOImpl.java
 create mode 100644 src/main/java/com/BoardMaria/dto/AddressVO.java
 create mode 100644 src/main/java/com/BoardMaria/dto/BoardVO.java
 create mode 100644 src/main/java/com/BoardMaria/dto/FileVO.java
 create mode 100644 src/main/java/com/BoardMaria/dto/LikeVO.java
 create mode 100644 src/main/java/com/BoardMaria/dto/User.java
 create mode 100644 src/main/java/com/BoardMaria/dto/UserVO.java
 create mode 100644 src/main/java/com/BoardMaria/dto/replyVO.java
 create mode 100644 src/main/java/com/BoardMaria/mapper/SFTestMapper.java
 create mode 100644 src/main/java/com/BoardMaria/service/BoardService.java
 create mode 100644 src/main/java/com/BoardMaria/service/BoardServiceImpl.java
 create mode 100644 src/main/java/com/BoardMaria/service/MasterService.java
 create mode 100644 src/main/java/com/BoardMaria/service/MasterServiceImpl.java
 create mode 100644 src/main/java/com/BoardMaria/service/UserService.java
 create mode 100644 src/main/java/com/BoardMaria/service/UserServiceImpl.java
 create mode 100644 src/main/java/com/BoardMaria/util/Page.java
 create mode 100644 src/main/resources/log4j.xml
 create mode 100644 src/main/resources/mappers/BoardMapper.xml
 create mode 100644 src/main/resources/mappers/MasterMapper.xml
 create mode 100644 src/main/resources/mappers/UserMapper.xml
 create mode 100644 src/main/resources/mybatis-config.xml
 create mode 100644 src/main/webapp/WEB-INF/spring/appServlet/servlet-context.xm
l
 create mode 100644 src/main/webapp/WEB-INF/spring/root-context.xml
 create mode 100644 src/main/webapp/WEB-INF/spring/spring-security.xml
 create mode 100644 src/main/webapp/WEB-INF/views/board/list.jsp
 create mode 100644 src/main/webapp/WEB-INF/views/board/modify.jsp
 create mode 100644 src/main/webapp/WEB-INF/views/board/view.jsp
 create mode 100644 src/main/webapp/WEB-INF/views/board/write.jsp
 create mode 100644 src/main/webapp/WEB-INF/views/home.jsp
 create mode 100644 src/main/webapp/WEB-INF/views/master/filemanage.jsp
 create mode 100644 src/main/webapp/WEB-INF/views/master/sysinfo.jsp
 create mode 100644 src/main/webapp/WEB-INF/views/master/sysmanage.jsp
 create mode 100644 src/main/webapp/WEB-INF/views/study/fileUpload.jsp
 create mode 100644 src/main/webapp/WEB-INF/views/study/fileUpload2.jsp
 create mode 100644 src/main/webapp/WEB-INF/views/study/filelist.jsp
 create mode 100644 src/main/webapp/WEB-INF/views/study/imgView.jsp
 create mode 100644 src/main/webapp/WEB-INF/views/study/imgViews.jsp
 create mode 100644 src/main/webapp/WEB-INF/views/user/IDView.jsp
 create mode 100644 src/main/webapp/WEB-INF/views/user/addrSearch.jsp
 create mode 100644 src/main/webapp/WEB-INF/views/user/login.jsp
 create mode 100644 src/main/webapp/WEB-INF/views/user/message.jsp
 create mode 100644 src/main/webapp/WEB-INF/views/user/pwCheckNotice.jsp
 create mode 100644 src/main/webapp/WEB-INF/views/user/searchID.jsp
 create mode 100644 src/main/webapp/WEB-INF/views/user/searchPassword.jsp
 create mode 100644 src/main/webapp/WEB-INF/views/user/signup.jsp
 create mode 100644 src/main/webapp/WEB-INF/views/user/tempPWView.jsp
 create mode 100644 src/main/webapp/WEB-INF/views/user/userInfoModify.jsp
 create mode 100644 src/main/webapp/WEB-INF/views/user/userPasswordModify.jsp
 create mode 100644 src/main/webapp/WEB-INF/views/user/userinfo.jsp
 create mode 100644 src/main/webapp/WEB-INF/web.xml
 create mode 100644 src/main/webapp/resources/css/board.css
 create mode 100644 src/main/webapp/resources/images/Judge.jpg
 create mode 100644 src/main/webapp/resources/images/logo.jpg
 create mode 100644 src/test/resources/log4j.xml
 create mode 100644 target/classes/com/BoardMaria/controller/BoardController.cla
ss
 create mode 100644 target/classes/com/BoardMaria/controller/BoardRestController
.class
 create mode 100644 target/classes/com/BoardMaria/controller/MasterController.cl
ass
 create mode 100644 target/classes/com/BoardMaria/controller/StudyController.cla
ss
 create mode 100644 target/classes/com/BoardMaria/controller/UserController.clas
s
 create mode 100644 target/classes/com/BoardMaria/dao/BoardDAO.class
 create mode 100644 target/classes/com/BoardMaria/dao/BoardDAOImpl.class
 create mode 100644 target/classes/com/BoardMaria/dao/MasterDAO.class
 create mode 100644 target/classes/com/BoardMaria/dao/MasterDAOImpl.class
 create mode 100644 target/classes/com/BoardMaria/dao/UserDAO.class
 create mode 100644 target/classes/com/BoardMaria/dao/UserDAOImpl.class
 create mode 100644 target/classes/com/BoardMaria/dto/AddressVO.class
 create mode 100644 target/classes/com/BoardMaria/dto/BoardVO.class
 create mode 100644 target/classes/com/BoardMaria/dto/FileVO.class
 create mode 100644 target/classes/com/BoardMaria/dto/LikeVO.class
 create mode 100644 target/classes/com/BoardMaria/dto/UserVO.class
 create mode 100644 target/classes/com/BoardMaria/dto/replyVO.class
 create mode 100644 target/classes/com/BoardMaria/mapper/SFTestMapper.class
 create mode 100644 target/classes/com/BoardMaria/service/BoardService.class
 create mode 100644 target/classes/com/BoardMaria/service/BoardServiceImpl.class

 create mode 100644 target/classes/com/BoardMaria/service/MasterService.class
 create mode 100644 target/classes/com/BoardMaria/service/MasterServiceImpl.clas
s
 create mode 100644 target/classes/com/BoardMaria/service/UserService.class
 create mode 100644 target/classes/com/BoardMaria/service/UserServiceImpl.class
 create mode 100644 target/classes/com/BoardMaria/util/Page.class
 create mode 100644 target/classes/log4j.xml
 create mode 100644 target/classes/mappers/BoardMapper.xml
 create mode 100644 target/classes/mappers/MasterMapper.xml
 create mode 100644 target/classes/mappers/UserMapper.xml
 create mode 100644 target/classes/mybatis-config.xml
 create mode 100644 target/m2e-wtp/web-resources/META-INF/MANIFEST.MF
 create mode 100644 target/m2e-wtp/web-resources/META-INF/maven/com.BoardMaria/c
ontroller/pom.properties
 create mode 100644 target/m2e-wtp/web-resources/META-INF/maven/com.BoardMaria/c
ontroller/pom.xml
 create mode 100644 target/m2e-wtp/web-resources/META-INF/maven/com.SFTest/contr
oller/pom.properties
 create mode 100644 target/m2e-wtp/web-resources/META-INF/maven/com.SFTest/contr
oller/pom.xml
 create mode 100644 target/test-classes/log4j.xml
 create mode 100644 workspace-sts-3.9.14.RELEASE/BoardMaria/target/m2e-wtp/web-r
esources/META-INF/MANIFEST.MF
 create mode 100644 workspace-sts-3.9.14.RELEASE/BoardMaria/target/m2e-wtp/web-r
esources/META-INF/maven/com.BoardMaria/controller/pom.properties
 create mode 100644 workspace-sts-3.9.14.RELEASE/BoardMaria/target/m2e-wtp/web-r
esources/META-INF/maven/com.BoardMaria/controller/pom.xml

aaa@DESKTOP-IQ2JT8K MINGW64 ~/git/BoardMaria/BoardMaria (master)
$ git push
