你在项目中是如何利用 GCP 的服务来实现 DevOps 实践的？请举例说明 ：
CI/CD 流水线构建 ：使用 GCP 的 Cloud Build 服务，它可以与 GitHub、Bitbucket 等代码仓库集成，实现代码提交后的自动构建、测试和部署。例如，当开发人员提交代码后，Cloud Build 会自动拉取代码，进行编译、运行测试用例，若测试通过则将应用部署到 GCP 的 App Engine 或 Compute Engine 上。
基础设施即代码（IaC）实践 ：借助 GCP 的 Deployment Manager 或 Terraform 等工具，将基础设施资源以代码的形式进行定义和管理。通过编写配置文件，可以一键创建和销毁 GCP 上的虚拟机、网络、存储等资源，实现基础设施的自动化部署和版本控制，确保环境的一致性和可重复性。
监控与日志管理 ：利用 GCP 的 Cloud Monitoring 和 Cloud Logging 服务，实时监控项目的各项指标，如应用性能、资源利用率等，并收集和分析日志信息。一旦发现异常，可以及时发出告警，方便运维人员快速定位和解决问题，提高系统的可靠性和稳定性
