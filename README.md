# spring-boot 系列学习 
jwt： http://blog.csdn.net/u011277123/article/details/78918390

## mybatis-plus  官方文档 http://mp.baomidou.com/#/quick-start

## MongoDB  
### 技术分享 https://weibo.com/ttarticle/p/show?id=2309404220699379163078#_0

## 配置Spring Boot通过@ConditionalOnProperty来控制Configuration是否生效

@Configuration
@EnableScheduling
@ConditionalOnProperty(prefix = "timedTask", name = "job-cheduleConfig-open", havingValue = "true")
public class ScheduleConfig  implements SchedulingConfigurer