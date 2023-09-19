泛影云是为了解决我国医学影像诊断过程中存在的基层医院误诊率高、偏远地区居民就诊不便、三甲医院影像专家工作量大等问题实现的一个医学影像诊断云平台。

泛影云在患者、基层医院医生和三甲医院专家间建立直接的沟通渠道，既可以使患者在当地就能享受到三甲医院的专家诊疗，从而大大节省了患者就医成本和就医时间，又可以使基层医院医生快速积累专业经验，从而加快基层医院的专业能力建设。同时，该系统对推动远程医疗、分级诊疗、优质医疗资源下沉、服务可及性和区域整体医疗水平的提升有着长足的影响，为我国医院信息化建设带来了空前机遇，大大提高人民获得感和幸福感。

在泛影云，你可以享受到各大医院影像科专家的一对一服务，便捷的享受到优质的医疗资源！

1、前端代码建议使用HBuilder X作为运行平台；

2、后端代码建议使用IntelliJ IDEA作为运行平台；

3、数据库建议使用MySQL 5版本;

4、前端代码的运行步骤：

     首先安装Node.js。然后在HBuilder X中打开前端代码文件“image_cloud”，鼠标右键项目名，选择“外部命令”，按顺序执行以下命令。（也可选择在项目所在路径下打开终端，顺序执行以下命令。）
     
     ## Project setup（仅首次运行时执行）
     npm install

     ## Compiles and hot-reloads for development
     npm run serve

     默认访问路径：http://localhost:8080/home.html/（可根据实际情况调整端口号）

     本项目支持多端部署，配置文件详情见"泛影云前端代码/src/components/ChooseEdge.vue"及"泛影云前端代码/public/config/backendapi.js"。
     
     如单机部署，请直接访问：http://xxx/login.html/或手动修改。

5、新建数据库。
     
     在终端或Navicat中运行“数据库结构文件”文件夹中的“cloud_image.sql”文件即可。

6、后端代码的运行步骤：
     
     首先在IntelliJ IDEA中打开后端代码文件“cloud_image”，打开“cloud_image->src->main->resources”中的“application.yml”文件，按实际情况修改数据库配置中的url中的端口号和数据库用户名和密码。
     
     最后，返回上级目录，运行“CloudImageApplication”文件。
