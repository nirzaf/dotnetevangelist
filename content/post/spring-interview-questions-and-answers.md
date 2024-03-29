---
title: "Spring Interview Questions and Answers"
date: 2021-10-15T19:51:17+05:30
draft: false
tags: ["spring"]
---

<img src="https://i.ibb.co/P4dQBcw/Spring-Interview-Questions-and-Answers.png" alt="Spring-Interview-Questions-and-Answers" border="0">
<ol>
<li><a href="#spring-overview">What is Spring Framework?</a></li>
<li><a href="#spring-advantages">What are some of the important features and advantages of Spring Framework?</a></li>
<li><a href="#dependency-injection">What do you understand by Dependency Injection?</a></li>
<li><a href="#spring-dependency-injection">How do we implement DI in Spring Framework?</a></li>
<li><a href="#spring-5">What are the new features in Spring 5?</a></li>
<li><a href="#spring-webflux">What is Spring WebFlux?</a></li>
<li><a href="#spring-tool-suite">What are the benefits of using Spring Tool Suite?</a></li>
<li><a href="#spring-modules">Name some of the important Spring Modules?</a></li>
<li><a href="#aspect-oriented-programming">What do you understand by Aspect Oriented Programming?</a></li>
<li><a href="#aspect-advice-pointcut-joinpoint">What is Aspect, Advice, Pointcut, JointPoint and Advice Arguments in AOP?</a></li>
<li><a href="#spring-vs-aspectj">What is the difference between Spring AOP and AspectJ AOP?</a></li>
<li><a href="#spring-ioc-container">What is Spring IoC Container?</a></li>
<li><a href="#spring-bean">What is a Spring Bean?</a></li>
<li><a href="#spring-bean-configuration-file">What is the importance of Spring bean configuration file?</a></li>
<li><a href="#spring-bean-configuration">What are different ways to configure a class as Spring Bean?</a></li>
<li><a href="#spring-bean-scopes">What are different scopes of Spring Bean?</a></li>
<li><a href="#spring-bean-life-cycle">What is Spring Bean life cycle?</a></li>
<li><a href="#servlet-context-config-spring-bean">How to get ServletContext and ServletConfig object in a Spring Bean?</a></li>
<li><a href="#bean-wiring-autowiring">What is Bean wiring and @Autowired annotation?</a></li>
<li><a href="#bean-autowire-types">What are different types of Spring Bean autowiring?</a></li>
<li><a href="#spring-bean-thread-safety">Does Spring Bean provide thread safety?</a></li>
<li><a href="#spring-controller-bean">What is a Controller in Spring MVC?</a></li>
<li><a href="#component-vs-controller-vs-service-vs-repository">What&#8217;s the difference between @Component, @Repository &#038; @Service annotations in Spring?</a></li>
<li><a href="#DispatcherServlet-ContextLoaderListener">What is DispatcherServlet and ContextLoaderListener?</a></li>
<li><a href="#spring-ViewResolver">What is ViewResolver in Spring?</a></li>
<li><a href="#MultipartResolver">What is a MultipartResolver and when it&#8217;s used?</a></li>
<li><a href="#spring-mvc-exceptions">How to handle exceptions in Spring MVC Framework?</a></li>
<li><a href="#java-ApplicationContext">How to create ApplicationContext in a Java Program?</a></li>
<li><a href="#multiple-context-files">Can we have multiple Spring configuration files?</a></li>
<li><a href="#ContextLoaderListener">What is ContextLoaderListener?</a></li>
<li><a href="#spring-mvc-hello-world">What are the minimum configurations needed to create Spring MVC application?</a></li>
<li><a href="#spring-mvc-architecture">How would you relate Spring MVC Framework to MVC architecture?</a></li>
<li><a href="#spring-localization-i18n">How to achieve localization in Spring MVC applications?</a></li>
<li><a href="#spring-restful-json">How can we use Spring to create Restful Web Service returning JSON response?</a></li>
<li><a href="#spring-annotations">What are some of the important Spring annotations you have used?</a></li>
<li><a href="#spring-object-response">Can we send an Object as the response of Controller handler method?</a></li>
<li><a href="#spring-mvc-file-upload">How to upload file in Spring MVC Application?</a></li>
<li><a href="#spring-mvc-form-validation">How to validate form data in Spring Web MVC Framework?</a></li>
<li><a href="#spring-mvc-interceptors">What is Spring MVC Interceptor and how to use it?</a></li>
<li><a href="#spring-jdbc-JdbcTemplate">What is Spring JdbcTemplate class and how to use it?</a></li>
<li><a href="#spring-tomcat-jndi-DataSource">How to use Tomcat JNDI DataSource in Spring Web Application?</a></li>
<li><a href="#spring-transaction-management">How would you achieve Transaction Management in Spring?</a></li>
<li><a href="#spring-DAO">What is Spring DAO?</a></li>
<li><a href="#spring-hibernate-integration">How to integrate Spring and Hibernate Frameworks?</a></li>
<li><a href="#spring-security">What is Spring Security?</a></li>
<li><a href="#spring-properties-inject">How to inject a java.util.Properties into a Spring Bean?</a></li>
<li><a href="#spring-design-patterns">Name some of the design patterns used in Spring Framework?</a></li>
<li><a href="#spring-best-practices">What are some of the best practices for Spring Framework?</a></li>
</ol>
<h2>Spring Interview Questions and Answers</h2>
<ol>
<a name="spring-overview"></a></p>
<li>
<h3>What is Spring Framework?</h3>
<p>Spring is one of the most widely used Java EE framework. Spring framework core concepts are &#8220;Dependency Injection&#8221; and &#8220;Aspect Oriented Programming&#8221;.</p>
<p>Spring framework can be used in normal java applications also to achieve loose coupling between different components by implementing dependency injection and we can perform cross-cutting tasks such as logging and authentication using spring support for aspect-oriented programming.</p>
<p>I like spring because it provides a lot of features and different modules for specific tasks such as Spring MVC and Spring JDBC. Since it&#8217;s an open source framework with a lot of online resources and active community members, working with the Spring framework is easy and fun at the same time. </p>
<p><strong>Recommended Read</strong>: <a href="https://www.journaldev.com/16922/spring-framework" rel="noopener noreferrer" target="_blank">Spring Framework</a>
</li>
<p><a name="spring-advantages"></a></p>
<li>
<h3>What are some of the important features and advantages of Spring Framework?</h3>
<p>Spring Framework is built on top of two design concepts &#8211; Dependency Injection and Aspect Oriented Programming.</p>
<p>Some of the features of spring framework are:</p>
<ul>
<li>Lightweight and very little overhead of using framework for our development.</li>
<li>Dependency Injection or Inversion of Control to write components that are independent of each other, spring container takes care of wiring them together to achieve our work.</li>
<li>Spring IoC container manages Spring Bean life cycle and project specific configurations such as JNDI lookup.</li>
<li>Spring MVC framework can be used to create web applications as well as restful web services capable of returning XML as well as JSON response.</li>
<li>Support for transaction management, JDBC operations, File uploading, Exception Handling etc with very little configurations, either by using annotations or by spring bean configuration file.</li>
</ul>
<p>Some of the advantages of using Spring Framework are:</p>
<ul>
<li>Reducing direct dependencies between different components of the application, usually Spring IoC container is responsible for initializing resources or beans and inject them as dependencies.</li>
<li>Writing unit test cases are easy in Spring framework because our business logic doesn&#8217;t have direct dependencies with actual resource implementation classes. We can easily write a test configuration and inject our mock beans for testing purposes.</li>
<li>Reduces the amount of boiler-plate code, such as initializing objects, open/close resources. I like JdbcTemplate class a lot because it helps us in removing all the boiler-plate code that comes with JDBC programming.</li>
<li>Spring framework is divided into several modules, it helps us in keeping our application lightweight. For example, if we don&#8217;t need Spring transaction management features, we don&#8217;t need to add that dependency on our project.</li>
<li>Spring framework support most of the Java EE features and even much more. It&#8217;s always on top of the new technologies, for example, there is a Spring project for Android to help us write better code for native <a href="https://www.journaldev.com/android" target="_blank" rel="noopener noreferrer">Android</a> applications. This makes spring framework a complete package and we don&#8217;t need to look after the different framework for different requirements.</li>
</ul>
</li>
<p><a name="dependency-injection"></a></p>
<li>
<h3>What do you understand by Dependency Injection?</h3>
<p>Dependency Injection <a href="https://www.journaldev.com/1827/java-design-patterns-example-tutorial">design pattern</a> allows us to remove the hard-coded dependencies and make our application loosely coupled, extendable and maintainable. We can implement dependency injection pattern to move the dependency resolution from compile-time to runtime.</p>
<p>Some of the benefits of using Dependency Injection are Separation of Concerns, Boilerplate Code reduction, Configurable components, and easy unit testing.</p>
<p>Read more at <a href="https://www.journaldev.com/2394/java-dependency-injection-design-pattern-example-tutorial" target="_blank" rel="noopener noreferrer">Dependency Injection Tutorial</a>. We can also use <a href="https://www.journaldev.com/2403/google-guice-dependency-injection-example-tutorial" target="_blank" rel="noopener noreferrer">Google Guice for Dependency Injection</a> to automate the process of dependency injection. But in most of the cases, we are looking for more than just dependency injection and that&#8217;s why Spring is the top choice for this.</p>
</li>
<p><a name="spring-dependency-injection"></a></p><div class='code-block code-block-5' style='margin: 8px auto; text-align: center; display: block; clear: both;'>
<div data-type="ad" data-publisher="journaldev.com" data-format="300x250" data-zone="jd_post_mid_300x250" ></div></div>

<li>
<h3>How do we implement DI in Spring Framework?</h3>
<p>We can use Spring XML based as well as Annotation-based configuration to implement DI in spring applications. For better understanding, please read <a href="https://www.journaldev.com/2410/spring-dependency-injection" target="_blank" rel="noopener noreferrer">Spring Dependency Injection</a> example where you can learn both the ways with JUnit test case. The post also contains a sample project zip file, that you can download and play around to learn more.</p>
</li>
<p><a name="spring-5"></a></p>
<li>
<h3>What are the new features in Spring 5?</h3>
<p>Spring 5 brought a massive update to Spring framework. Some of the new features in Spring 5 are:</p>
<ol>
<li>Spring 5 runs on <a href="https://www.journaldev.com/2389/java-8-features-with-examples">Java 8</a>+ and supports Java EE 7. So we can use lambda expressions and Servlet 4.0 features. It&#8217;s good to see Spring trying to support the latest versions.</li>
<li>Spring Framework 5.0 comes with its own Commons Logging bridge; spring-jcl instead of standard Commons Logging.</li>
<li>Support for providing spring components information through index file “META-INF/spring.components” rather than classpath scanning.</li>
<li>Spring WebFlux brings reactive programming to the Spring Framework.</li>
<li>Spring 5 also supports Kotlin programming now. This is a huge step towards supporting functional programming, just as Java is also moving towards functional programming.</li>
<li>Support for JUnit 5 and parallel testing execution in the Spring TestContext Framework.</li>
</ol>
<p>You can read about these features in more detail at <a href="https://www.journaldev.com/20714/spring-5" rel="noopener noreferrer" target="_blank">Spring 5 Features</a>.
</li>
<p><a name="spring-webflux"></a></p>
<li>
<h3>What is Spring WebFlux?</h3>
<p>Spring WebFlux is the new module introduced in Spring 5. Spring WebFlux is the first step towards the reactive programming model in spring framework.</p>
<p>Spring WebFlux is the alternative to the Spring MVC module. Spring WebFlux is used to create a fully asynchronous and non-blocking application built on the event-loop execution model.</p>
<p>You can read more about it at <a href="https://www.journaldev.com/20763/spring-webflux-reactive-programming" rel="noopener noreferrer" target="_blank">Spring WebFlux Tutorial</a>.
</li>
<p><a name="spring-tool-suite"></a></p>
<li>
<h3>What are the benefits of using Spring Tool Suite?</h3>
<p>We can install plugins into Eclipse to get all the features of Spring Tool Suite. However, STS comes with Eclipse with some other important kinds of stuff such as Maven support, Templates for creating different types of Spring projects and tc server for better performance with Spring applications.</p>
<p>I like STS because it highlights the Spring components and if you are using AOP pointcuts and advice, then it clearly shows which methods will come under the specific pointcut. So rather than installing everything on our own, I prefer using STS when developing Spring-based applications.
</li>
<p><a name="spring-modules"></a></p>
<li>
<h3>Name some of the important Spring Modules?</h3>
<p>Some of the important Spring Framework modules are:</p>
<ul>
<li><strong>Spring Context</strong> &#8211; for dependency injection.</li>
<li><strong>Spring AOP</strong> &#8211; for aspect oriented programming.</li>
<li><strong>Spring DAO</strong> &#8211; for database operations using DAO pattern</li>
<li><strong>Spring JDBC</strong> &#8211; for JDBC and DataSource support.</li>
<li><strong>Spring ORM</strong> &#8211; for ORM tools support such as Hibernate</li>
<li><strong>Spring Web Module</strong> &#8211; for creating web applications.</li>
<li><strong>Spring MVC</strong> &#8211; Model-View-Controller implementation for creating web applications, web services etc.</li>
</ul>
</li>
<p><a name="aspect-oriented-programming"></a></p>
<li>
<h3>What do you understand by Aspect Oriented Programming?</h3>
<p>Enterprise applications have some common cross-cutting concerns that are applicable to different types of Objects and application modules, such as logging, transaction management, data validation, authentication etc. In Object Oriented Programming, modularity of application is achieved by Classes whereas in AOP application modularity is achieved by Aspects and they are configured to cut across different classes methods.</p>
<p>AOP takes out the direct dependency of cross-cutting tasks from classes that are not possible in normal object-oriented programming. For example, we can have a separate class for logging but again the classes will have to call these methods for logging the data. Read more about Spring AOP support at <a href="https://www.journaldev.com/2583/spring-aop-example-tutorial-aspect-advice-pointcut-joinpoint-annotations" target="_blank" rel="noopener noreferrer">Spring AOP Example</a>.</p>
</li>
<p><a name="aspect-advice-pointcut-joinpoint"></a></p>
<li>
<h3>What is Aspect, Advice, Pointcut, JointPoint and Advice Arguments in AOP?</h3>
<p><strong>Aspect</strong>: Aspect is a class that implements cross-cutting concerns, such as transaction management. Aspects can be a normal class configured and then configured in Spring Bean configuration file or we can use Spring AspectJ support to declare a class as Aspect using <code>@Aspect</code> annotation.</p>
<p><strong>Advice</strong>: Advice is the action taken for a particular join point. In terms of programming, they are methods that gets executed when a specific join point with matching pointcut is reached in the application. You can think of Advices as <a href="https://www.journaldev.com/2676/spring-mvc-interceptor-example-handlerinterceptor-handlerinterceptoradapter" target="_blank" rel="noopener noreferrer">Spring interceptors</a> or <a href="https://www.journaldev.com/1933/java-servlet-filter-example-tutorial" target="_blank" rel="noopener noreferrer">Servlet Filters</a>.</p>
<p><strong>Pointcut</strong>: Pointcut are regular expressions that are matched with join points to determine whether advice needs to be executed or not. Pointcut uses different kinds of expressions that are matched with the join points. Spring framework uses the AspectJ pointcut expression language for determining the join points where advice methods will be applied.</p>
<p><strong>Join Point</strong>: A join point is a specific point in the application such as method execution, exception handling, changing object variable values etc. In Spring AOP a join point is always the execution of a method.</p>
<p><strong>Advice Arguments</strong>: We can pass arguments in the advice methods. We can use args() expression in the pointcut to be applied to any method that matches the argument pattern. If we use this, then we need to use the same name in the advice method from where the argument type is determined. </p>
<p>These concepts seems confusing at first, but if you go through <a href="https://www.journaldev.com/2583/spring-aop-example-tutorial-aspect-advice-pointcut-joinpoint-annotations" target="_blank" rel="noopener noreferrer">Spring Aspect, Advice Example</a> then you can easily relate to them.
</li>
<p><a name="spring-vs-aspectj"></a></p>
<li>
<h3>What is the difference between Spring AOP and AspectJ AOP?</h3>
<p>AspectJ is the industry-standard implementation for Aspect Oriented Programming whereas Spring implements AOP for some cases. Main differences between Spring AOP and AspectJ are:</p>
<ul>
<li>Spring AOP is simpler to use than AspectJ because we don&#8217;t need to worry about the weaving process.</li>
<li>Spring AOP supports AspectJ annotations, so if you are familiar with AspectJ then working with Spring AOP is easier.</li>
<li>Spring AOP supports only proxy-based AOP, so it can be applied only to method execution join points. AspectJ support all kinds of pointcuts.</li>
<li>One of the shortcomings of Spring AOP is that it can be applied only to the beans created through Spring Context.</li>
</ul>
</li>
<p><a name="spring-ioc-container"></a></p>
<li>
<h3>What is Spring IoC Container?</h3>
<p><strong>Inversion of Control</strong> (IoC) is the mechanism to achieve loose-coupling between Objects dependencies. To achieve loose coupling and dynamic binding of the objects at runtime, the objects define their dependencies that are being injected by other assembler objects. Spring IoC container is the program that injects dependencies into an object and makes it ready for our use.</p>
<p>Spring Framework IoC container classes are part of <code>org.springframework.beans</code> and <code>org.springframework.context</code> packages and provides us different ways to decouple the object dependencies.</p>
<p>Some of the useful ApplicationContext implementations that we use are;</p>
<ul>
<li><code>AnnotationConfigApplicationContext</code>: For standalone java applications using annotations based configuration.</li>
<li><code>ClassPathXmlApplicationContext</code>: For standalone java applications using XML based configuration.</li>
<li><code>FileSystemXmlApplicationContext</code>: Similar to ClassPathXmlApplicationContext except that the xml configuration file can be loaded from anywhere in the file system.</li>
<li><code>AnnotationConfigWebApplicationContext</code> and <code>XmlWebApplicationContext</code> for web applications.</li>
</ul>
</li>
<p><a name="spring-bean"></a></p>
<li>
<h3>What is a Spring Bean?</h3>
<p>Any normal java class that is initialized by Spring IoC container is called Spring Bean. We use Spring <code>ApplicationContext</code> to get the Spring Bean instance. </p>
<p>Spring IoC container manages the life cycle of Spring Bean, bean scopes and injecting any required dependencies in the bean.</p>
</li>
<p><a name="spring-bean-configuration-file"></a></p>
<li>
<h3>What is the importance of Spring bean configuration file?</h3>
<p>We use Spring Bean configuration file to define all the beans that will be initialized by Spring Context. When we create the instance of Spring ApplicationContext, it reads the spring bean XML file and initializes all of them. Once the context is initialized, we can use it to get different bean instances.</p>
<p>Apart from Spring Bean configuration, this file also contains spring MVC interceptors, view resolvers and other elements to support annotations based configurations.</p>
</li>
<p><a name="spring-bean-configuration"></a></p>
<li>
<h3>What are different ways to configure a class as Spring Bean?</h3>
<p>There are three different ways to configure Spring Bean.</p>
<ol>
<li><strong>XML Configuration</strong>: This is the most popular configuration and we can use bean element in context file to configure a Spring Bean. For example:
<pre><code>
&lt;bean name="myBean" class="com.journaldev.spring.beans.MyBean"&gt;&lt;/bean&gt;
</code></pre>
</li>
<li><strong>Java Based Configuration</strong>: If you are using only annotations, you can configure a Spring bean using <code>@Bean</code> annotation. This annotation is used with <code>@Configuration</code> classes to configure a spring bean. Sample configuration is:
<pre><code>
@Configuration
@ComponentScan(value="com.journaldev.spring.main")
public class MyConfiguration {

	@Bean
	public MyService getService(){
		return new MyService();
	}
}
</code></pre>
<p>To get this bean from spring context, we need to use following code snippet:</p>
<pre><code>
AnnotationConfigApplicationContext ctx = new AnnotationConfigApplicationContext(
		MyConfiguration.class);
MyService service = ctx.getBean(MyService.class);
</code></pre>
</li>
<li><strong>Annotation Based Configuration</strong>: We can also use @Component, @Service, @Repository and @Controller annotations with classes to configure them to be as spring bean. For these, we would need to provide base package location to scan for these classes. For example:
<pre><code>
&lt;context:component-scan base-package="com.journaldev.spring" /&gt;
</code></pre>
</li>
</ol>
</li>
<p><a name="spring-bean-scopes"></a></p>
<li>
<h3>What are different scopes of Spring Bean?</h3>
<p>There are five scopes defined for Spring Beans.</p>
<ol>
<li><strong><a href="https://www.journaldev.com/1377/java-singleton-design-pattern-best-practices-examples">singleton</a></strong>: Only one instance of the bean will be created for each container. This is the default scope for the spring beans. While using this scope, make sure spring bean doesn&#8217;t have shared instance variables otherwise it might lead to data inconsistency issues because it&#8217;s not thread-safe.</li>
<li><strong>prototype</strong>: A new instance will be created every time the bean is requested.</li>
<li><strong>request</strong>: This is same as prototype scope, however it&#8217;s meant to be used for web applications. A new instance of the bean will be created for each HTTP request.</li>
<li><strong>session</strong>: A new bean will be created for each HTTP session by the container.</li>
<li><strong>global-session</strong>: This is used to create global session beans for Portlet applications.</li>
</ol>
<p>Spring Framework is extendable and we can create our own scopes too, however most of the times we are good with the scopes provided by the framework.</p>
<p>To set spring bean scopes we can use &#8220;scope&#8221; attribute in bean element or @Scope annotation for annotation based configurations. </p>
</li>
<p><a name="spring-bean-life-cycle"></a></p>
<li>
<h3>What is Spring Bean life cycle?</h3>
<p>Spring Beans are initialized by Spring Container and all the dependencies are also injected. When the context is destroyed, it also destroys all the initialized beans. This works well in most of the cases but sometimes we want to initialize other resources or do some validation before making our beans ready to use. Spring framework provides support for post-initialization and pre-destroy methods in spring beans.</p>
<p>We can do this by two ways &#8211; by implementing <code>InitializingBean</code> and <code>DisposableBean</code> interfaces or using <strong>init-method</strong> and <strong>destroy-method</strong> attribute in spring bean configurations. For more details, please read <a href="https://www.journaldev.com/2637/spring-bean-life-cycle" target="_blank" rel="noopener noreferrer">Spring Bean Life Cycle Methods</a>. </p>
</li>
<p><a name="servlet-context-config-spring-bean"></a></p>
<li>
<h3>How to get ServletContext and ServletConfig object in a Spring Bean?</h3>
<p>There are two ways to get Container specific objects in the spring bean.</p>
<ol>
<li>Implementing Spring *Aware interfaces, for these ServletContextAware and ServletConfigAware interfaces, for complete example of these aware interfaces, please read <a href="https://www.journaldev.com/2637/spring-bean-life-cycle" target="_blank" rel="noopener noreferrer">Spring Aware Interfaces</a></li>
<li>Using <code>@Autowired</code> annotation with bean variable of type <code>ServletContext</code> and <code>ServletConfig</code>. They will work only in servlet container specific environment only though.
<pre><code>
@Autowired
ServletContext servletContext;
</code></pre>
</li>
</ol>
</li>
<p><a name="bean-wiring-autowiring"></a></p>
<li>
<h3>What is Bean wiring and @Autowired annotation?</h3>
<p>The process of injection spring bean dependencies while initializing it called Spring Bean Wiring.</p>
<p>Usually, it&#8217;s best practice to do the explicit wiring of all the bean dependencies, but the spring framework also supports auto-wiring. We can use <code>@Autowired</code> annotation with fields or methods for <strong>autowiring byType</strong>. For this annotation to work, we also need to enable annotation-based configuration in spring bean configuration file. This can be done by <strong>context:annotation-config</strong> element.</p>
<p>For more details about <code>@Autowired</code> annotation, please read <a href="https://www.journaldev.com/2623/spring-autowired-annotation" target="_blank" rel="noopener noreferrer">Spring Autowire Example</a>.</p>
</li>
<p><a name="bean-autowire-types"></a></p>
<li>
<h3>What are different types of Spring Bean autowiring?</h3>
<p>There are four types of autowiring in Spring framework.</p>
<ol>
<li><strong>autowire byName</strong></li>
<li><strong>autowire byType</strong></li>
<li><strong>autowire by constructor</strong></li>
<li>autowiring by <strong>@Autowired</strong> and <strong>@Qualifier</strong> annotations</li>
</ol>
<p>Prior to Spring 3.1, <strong>autowire by autodetect</strong> was also supported that was similar to autowire by constructor or byType. For more details about these options, please read <a href="https://www.journaldev.com/2623/spring-autowired-annotation" target="_blank" rel="noopener noreferrer">Spring Bean Autowiring</a>.
</li>
<p><a name="spring-bean-thread-safety"></a></p>
<li>
<h3>Does Spring Bean provide thread safety?</h3>
<p>The default scope of Spring bean is singleton, so there will be only one instance per context. That means that all the having a class level variable that any thread can update will lead to inconsistent data. Hence in default mode spring beans are not thread-safe.</p>
<p>However, we can change spring bean scope to request, prototype or session to achieve thread-safety at the cost of performance. It&#8217;s a design decision and based on the project requirements.
</li>
<p><a name="spring-controller-bean"></a></p>
<li>
<h3>What is a Controller in Spring MVC?</h3>
<p>Just like MVC design pattern, Controller is the class that takes care of all the client requests and send them to the configured resources to handle it. In Spring MVC, <code>org.springframework.web.servlet.DispatcherServlet</code> is the front controller class that initializes the context based on the spring beans configurations.</p>
<p>A Controller class is responsible to handle a different kind of client requests based on the request mappings. We can create a controller class by using <code>@Controller</code> annotation. Usually, it&#8217;s used with <code>@RequestMapping</code> annotation to define handler methods for specific URI mapping. </p>
</li>
<p><a name="component-vs-controller-vs-service-vs-repository"></a></p>
<li>
<h3>What&#8217;s the difference between @Component, @Controller, @Repository &#038; @Service annotations in Spring?</h3>
<p><strong>@Component</strong> is used to indicate that a class is a component. These classes are used for auto-detection and configured as bean when annotation based configurations are used. </p>
<p><strong>@Controller</strong> is a specific type of component, used in MVC applications and mostly used with RequestMapping annotation.</p>
<p><strong>@Repository</strong> annotation is used to indicate that a component is used as repository and a mechanism to store/retrieve/search data. We can apply this annotation with DAO pattern implementation classes.</p>
<p><strong>@Service</strong> is used to indicate that a class is a Service. Usually, the business facade classes that provide some services are annotated with this.</p>
<p>We can use any of the above annotations for a class for auto-detection but different types are provided so that you can easily distinguish the purpose of the annotated classes.</p>
</li>
<p><a name="DispatcherServlet-ContextLoaderListener"></a></p><div class='code-block code-block-3 ai-viewport-1' style='margin: 8px auto; text-align: center; display: block; clear: both;'>
<div data-type="ad" data-publisher="journaldev.com" data-zone="jd_middle_post_desktop" data-format="728x90"> </div></div>

<li>
<h3>What is DispatcherServlet and ContextLoaderListener?</h3>
<p><code>DispatcherServlet</code> is the front controller in the Spring MVC application and it loads the spring bean configuration file and initialize all the beans that are configured. If annotations are enabled, it also scans the packages and configure any bean annotated with <code>@Component</code>, <code>@Controller</code>, <code>@Repository</code> or <code>@Service</code> annotations.</p>
<p><code>ContextLoaderListener</code> is the listener to start up and shut down Spring&#8217;s root <code>WebApplicationContext</code>. It&#8217;s important functions are to tie up the lifecycle of <code>ApplicationContext</code> to the lifecycle of the <code>ServletContext</code> and to automate the creation of <code>ApplicationContext</code>. We can use it to define shared beans that can be used across different spring contexts.</p>
</li>
<p><a name="spring-ViewResolver"></a></p>
<li>
<h3>What is ViewResolver in Spring?</h3>
<p><code>ViewResolver</code> implementations are used to resolve the view pages by name. Usually we configure it in the spring bean configuration file. For example:</p>
<pre><code>
&lt;!-- Resolves views selected for rendering by @Controllers to .jsp resources in the /WEB-INF/views directory --&gt;
&lt;beans:bean class="org.springframework.web.servlet.view.InternalResourceViewResolver"&gt;
	&lt;beans:property name="prefix" value="/WEB-INF/views/" /&gt;
	&lt;beans:property name="suffix" value=".jsp" /&gt;
&lt;/beans:bean&gt;
</code></pre>
<p><code>InternalResourceViewResolver</code> is one of the implementation of <code>ViewResolver</code> interface and we are providing the view pages directory and suffix location through the bean properties. So if a controller handler method returns &#8220;home&#8221;, view resolver will use view page located at <em>/WEB-INF/views/home.jsp</em>.</p>
</li>
<p><a name="MultipartResolver"></a></p>
<li>
<h3>What is a MultipartResolver and when it&#8217;s used?</h3>
<p><code>MultipartResolver</code> interface is used for uploading files &#8211; <code>CommonsMultipartResolver</code> and <code>StandardServletMultipartResolver</code> are two implementations provided by spring framework for file uploading. By default there are no multipart resolvers configured but to use them for uploading files, all we need to define a bean named &#8220;multipartResolver&#8221; with type as MultipartResolver in spring bean configurations.</p>
<p>Once configured, any multipart request will be resolved by the configured MultipartResolver and pass on a wrapped HttpServletRequest. Then it&#8217;s used in the controller class to get the file and process it. For a complete example, please read <a href="https://www.journaldev.com/2573/spring-mvc-file-upload-example-single-multiple-files" target="_blank" rel="noopener noreferrer">Spring MVC File Upload Example</a>.</p>
</li>
<p><a name="spring-mvc-exceptions"></a></p>
<li>
<h3>How to handle exceptions in Spring MVC Framework?</h3>
<p>Spring MVC Framework provides the following ways to help us achieving robust exception handling.</p>
<ol>
<li><strong>Controller Based</strong> – We can define exception handler methods in our controller classes. All we need is to annotate these methods with @ExceptionHandler annotation.</li>
<li><strong>Global Exception Handler</strong> – Exception Handling is a cross-cutting concern and Spring provides @ControllerAdvice annotation that we can use with any class to define our global exception handler.</li>
<li><strong>HandlerExceptionResolver implementation</strong> – For generic exceptions, most of the times we serve static pages. Spring Framework provides <code>HandlerExceptionResolver</code> interface that we can implement to create global exception handler. The reason behind this additional way to define global exception handler is that Spring framework also provides default implementation classes that we can define in our spring bean configuration file to get spring framework exception handling benefits.</li>
</ol>
<p>For a complete example, please read <a href="https://www.journaldev.com/2651/spring-mvc-exception-handling-controlleradvice-exceptionhandler-handlerexceptionresolver" target="_blank" rel="noopener noreferrer">Spring Exception Handling Example</a>.
</li>
<p><a name="java-ApplicationContext"></a></p>
<li>
<h3>How to create ApplicationContext in a Java Program?</h3>
<p>There are following ways to create spring context in a standalone java program.</p>
<ol>
<li><strong>AnnotationConfigApplicationContext</strong>: If we are using Spring in standalone java applications and using annotations for Configuration, then we can use this to initialize the container and get the bean objects.</li>
<li><strong>ClassPathXmlApplicationContext</strong>: If we have spring bean configuration xml file in standalone application, then we can use this class to load the file and get the container object.</li>
<li><strong>FileSystemXmlApplicationContext</strong>: This is similar to ClassPathXmlApplicationContext except that the xml configuration file can be loaded from anywhere in the file system.</li>
</ol>
</li>
<p><a name="multiple-context-files"></a></p>
<li>
<h3>Can we have multiple Spring configuration files?</h3>
<p>For Spring MVC applications, we can define multiple spring context configuration files through <code>contextConfigLocation</code>. This location string can consist of multiple locations separated by any number of commas and spaces. For example;</p>
<pre><code>
&lt;servlet&gt;
	&lt;servlet-name&gt;appServlet&lt;/servlet-name&gt;
	&lt;servlet-class&gt;org.springframework.web.servlet.DispatcherServlet&lt;/servlet-class&gt;
	&lt;init-param&gt;
            &lt;param-name&gt;contextConfigLocation&lt;/param-name&gt;
	    &lt;param-value&gt;/WEB-INF/spring/appServlet/servlet-context.xml,/WEB-INF/spring/appServlet/servlet-jdbc.xml&lt;/param-value&gt;
	&lt;/init-param&gt;
	&lt;load-on-startup&gt;1&lt;/load-on-startup&gt;
&lt;/servlet&gt;
</code></pre>
<p>We can also define multiple root level spring configurations and load it through context-param. For example;</p>
<pre><code>
&lt;context-param&gt;
	&lt;param-name&gt;contextConfigLocation&lt;/param-name&gt;
	&lt;param-value&gt;/WEB-INF/spring/root-context.xml /WEB-INF/spring/root-security.xml&lt;/param-value&gt;
&lt;/context-param&gt;
</code></pre>
<p>Another option is to use import element in the context configuration file to import other configurations, for example:</p>
<pre><code>
&lt;beans:import resource="spring-jdbc.xml"/&gt;
</code></pre>
</li>
<p><a name="ContextLoaderListener"></a></p>
<li>
<h3>What is ContextLoaderListener?</h3>
<p>ContextLoaderListener is the listener class used to load root context and define spring bean configurations that will be visible to all other contexts. It&#8217;s configured in web.xml file as:</p>
<pre><code>
&lt;context-param&gt;
	&lt;param-name&gt;contextConfigLocation&lt;/param-name&gt;
	&lt;param-value&gt;/WEB-INF/spring/root-context.xml&lt;/param-value&gt;
&lt;/context-param&gt;
	
&lt;listener&gt;
	&lt;listener-class&gt;org.springframework.web.context.ContextLoaderListener&lt;/listener-class&gt;
&lt;/listener&gt;
</code></pre>
</li>
<p><a name="spring-mvc-hello-world"></a></p>
<li>
<h3>What are the minimum configurations needed to create Spring MVC application?</h3>
<p>For creating a simple Spring MVC application, we would need to do the following tasks.</p>
<ul>
<li>Add <code>spring-context</code> and <code>spring-webmvc</code> dependencies in the project.</li>
<li>Configure <code>DispatcherServlet</code> in the web.xml file to handle requests through spring container.</li>
<li>Spring bean configuration file to define beans, if using annotations then it has to be configured here. Also we need to configure view resolver for view pages.</li>
<li>Controller class with request mappings defined to handle the client requests.</li>
</ul>
</li>
<p>Above steps should be enough to create a simple Spring MVC Hello World application.<br />
<a name="spring-mvc-architecture"></a></p>
<li>
<h3>How would you relate Spring MVC Framework to MVC architecture?</h3>
<p>As the name suggests Spring MVC is built on top of <strong>Model-View-Controller</strong> architecture. <code>DispatcherServlet</code> is the Front Controller in the Spring MVC application that takes care of all the incoming requests and delegate it to different controller handler methods.</p>
<p>The model can be any Java Bean in the Spring Framework, just like any other MVC framework Spring provides automatic binding of form data to java beans. We can set model beans as attributes to be used in the view pages.</p>
<p>View Pages can be JSP, static HTMLs etc. and view resolvers are responsible for finding the correct view page. Once the view page is identified, control is given back to the DispatcherServlet controller. DispatcherServlet is responsible for rendering the view and returning the final response to the client.
</li>
<p><a name="spring-localization-i18n"></a></p>
<li>
<h3>How to achieve localization in Spring MVC applications?</h3>
<p>Spring provides excellent support for localization or i18n through resource bundles. Basis steps needed to make our application localized are:</p>
<ol>
<li>Creating message resource bundles for different locales, such as messages_en.properties, messages_fr.properties etc.</li>
<li>Defining messageSource bean in the spring bean configuration file of type <code>ResourceBundleMessageSource</code> or <code>ReloadableResourceBundleMessageSource</code>.</li>
<li>For change of locale support, define localeResolver bean of type CookieLocaleResolver and configure LocaleChangeInterceptor interceptor. Example configuration can be like below:
<pre><code>
&lt;beans:bean id="messageSource"
class="org.springframework.context.support.ReloadableResourceBundleMessageSource"&gt;
&lt;beans:property name="basename" value="classpath:messages" /&gt;
&lt;beans:property name="defaultEncoding" value="UTF-8" /&gt;
&lt;/beans:bean&gt;
 
&lt;beans:bean id="localeResolver"
    class="org.springframework.web.servlet.i18n.CookieLocaleResolver"&gt;
    &lt;beans:property name="defaultLocale" value="en" /&gt;
    &lt;beans:property name="cookieName" value="myAppLocaleCookie"&gt;&lt;/beans:property&gt;
    &lt;beans:property name="cookieMaxAge" value="3600"&gt;&lt;/beans:property&gt;
&lt;/beans:bean&gt;
 
&lt;interceptors&gt;
    &lt;beans:bean class="org.springframework.web.servlet.i18n.LocaleChangeInterceptor"&gt;
        &lt;beans:property name="paramName" value="locale" /&gt;
    &lt;/beans:bean&gt;
&lt;/interceptors&gt;
</code></pre>
</li>
<li>Use <code>spring:message</code> element in the view pages with key names, DispatcherServlet picks the corresponding value and renders the page in corresponding locale and return as response.</li>
</ol>
<p>For a complete example, please read <a href="https://www.journaldev.com/2610/spring-mvc-internationalization-i18n-and-localization-l10n-example" target="_blank" rel="noopener noreferrer">Spring Localization Example</a>.
</li>
<p><a name="spring-restful-json"></a></p>
<li>
<h3>How can we use Spring to create Restful Web Service returning JSON response?</h3>
<p>We can use Spring Framework to create Restful web services that returns JSON data. Spring provides integration with <a href="https://www.journaldev.com/2324/jackson-json-java-parser-api-example-tutorial" target="_blank" rel="noopener noreferrer">Jackson JSON</a> API that we can use to send JSON response in restful web service.</p>
<p>We would need to do following steps to configure our Spring MVC application to send JSON response:</p>
<ol>
<li>Adding Jackson JSON dependencies, if you are using Maven it can be done with following code:
<pre><code>
&lt;!-- Jackson --&gt;
&lt;dependency&gt;
    &lt;groupId&gt;com.fasterxml.jackson.core&lt;/groupId&gt;
    &lt;artifactId&gt;jackson-databind&lt;/artifactId&gt;
    &lt;version&gt;${jackson.databind-version}&lt;/version&gt;
&lt;/dependency&gt;
</code></pre>
</li>
<li>Configure <code>RequestMappingHandlerAdapter</code> bean in the spring bean configuration file and set the messageConverters property to MappingJackson2HttpMessageConverter bean. Sample configuration will be:
<pre><code>
&lt;!-- Configure to plugin JSON as request and response in method handler --&gt;
&lt;beans:bean class="org.springframework.web.servlet.mvc.method.annotation.RequestMappingHandlerAdapter"&gt;
    &lt;beans:property name="messageConverters"&gt;
        &lt;beans:list&gt;
            &lt;beans:ref bean="jsonMessageConverter"/&gt;
        &lt;/beans:list&gt;
    &lt;/beans:property&gt;
&lt;/beans:bean&gt;
     
&lt;!-- Configure bean to convert JSON to POJO and vice versa --&gt;
&lt;beans:bean id="jsonMessageConverter" class="org.springframework.http.converter.json.MappingJackson2HttpMessageConverter"&gt;
&lt;/beans:bean&gt;
</code></pre>
</li>
<li>In the controller handler methods, return the Object as response using <code>@ResponseBody</code> annotation. Sample code:
<pre><code>
@RequestMapping(value = EmpRestURIConstants.GET_EMP, method = RequestMethod.GET)
public @ResponseBody Employee getEmployee(@PathVariable("id") int empId) {
    logger.info("Start getEmployee. ID="+empId);
     
    return empData.get(empId);
}
</code></pre>
</li>
<li>You can invoke the rest service through any API, but if you want to use Spring then we can easily do it using RestTemplate class.</li>
</ol>
<p>For a complete example, please read <a href="https://www.journaldev.com/2552/spring-rest-example-tutorial-spring-restful-web-services" target="_blank" rel="noopener noreferrer">Spring Restful Webservice Example</a>.
</li>
<p><a name="spring-annotations"></a></p>
<li>
<h3>What are some of the important Spring annotations you have used?</h3>
<p>Some of the Spring annotations that I have used in my project are:</p>
<ul>
<li><strong>@Controller</strong> &#8211; for controller classes in Spring MVC project.</li>
<li><strong>@RequestMapping</strong> &#8211; for configuring URI mapping in controller handler methods. This is a very important annotation, so you should go through <a href="https://www.journaldev.com/3358/spring-requestmapping-requestparam-pathvariable-example" target="_blank" rel="noopener noreferrer">Spring MVC RequestMapping Annotation Examples</a></li>
<li><strong>@ResponseBody</strong> &#8211; for sending Object as response, usually for sending XML or JSON data as response.</li>
<li><strong>@PathVariable</strong> &#8211; for mapping dynamic values from the URI to handler method arguments.</li>
<li><strong>@Autowired</strong> &#8211; for autowiring dependencies in spring beans.</li>
<li><strong>@Qualifier</strong> &#8211; with @Autowired annotation to avoid confusion when multiple instances of bean type is present.</li>
<li><strong>@Service</strong> &#8211; for service classes.</li>
<li><strong>@Scope</strong> &#8211; for configuring scope of the spring bean.</li>
<li><strong>@Configuration</strong>, <strong>@ComponentScan</strong> and <strong>@Bean</strong> &#8211; for java based configurations.</li>
<li>AspectJ annotations for configuring aspects and advices, <strong>@Aspect</strong>, <strong>@Before</strong>, <strong>@After</strong>, <strong>@Around</strong>, <strong>@Pointcut</strong> etc.</li>
</ul>
</li>
<p><a name="spring-object-response"></a></p>
<li>
<h3>Can we send an Object as the response of Controller handler method?</h3>
<p>Yes we can, using <strong>@ResponseBody</strong> annotation. This is how we send JSON or XML based response in restful web services.</p>
</li>
<p><a name="spring-mvc-file-upload"></a></p>
<li>
<h3>How to upload file in Spring MVC Application?</h3>
<p>Spring provides built-in support for uploading files through <strong>MultipartResolver</strong> interface implementations. It&#8217;s very easy to use and requires only configuration changes to get it working. Obviously we would need to write controller handler method to handle the incoming file and process it. For a complete example, please refer <a href="https://www.journaldev.com/2573/spring-mvc-file-upload-example-single-multiple-files" target="_blank" rel="noopener noreferrer">Spring File Upload Example</a>.</p>
</li>
<p><a name="spring-mvc-form-validation"></a></p>
<li>
<h3>How to validate form data in Spring Web MVC Framework?</h3>
<p>Spring supports JSR-303 annotation based validations as well as provide Validator interface that we can implement to create our own custom validator. For using JSR-303 based validation, we need to annotate bean variables with the required validations.</p>
<p>For custom validator implementation, we need to configure it in the controller class. For a complete example, please read <a href="https://www.journaldev.com/2668/spring-validation-example-mvc-validator" target="_blank" rel="noopener noreferrer">Spring MVC Form Validation Example</a>.</p>
</li>
<p><a name="spring-mvc-interceptors"></a></p>
<li>
<h3>What is Spring MVC Interceptor and how to use it?</h3>
<p>Spring MVC Interceptors are like Servlet Filters and allow us to intercept client request and process it. We can intercept client request at three places &#8211; <strong>preHandle</strong>, <strong>postHandle</strong> and <strong>afterCompletion</strong>.</p>
<p>We can create spring interceptor by implementing HandlerInterceptor interface or by extending abstract class <strong>HandlerInterceptorAdapter</strong>.</p>
<p>We need to configure interceptors in the spring bean configuration file. We can define an interceptor to intercept all the client requests or we can configure it for specific URI mapping too. For a detailed example, please refer <a href="https://www.journaldev.com/2676/spring-mvc-interceptor-example-handlerinterceptor-handlerinterceptoradapter">Spring MVC Interceptor Example</a>.
</li>
<p><a name="spring-jdbc-JdbcTemplate"></a></p>
<li>
<h3>What is Spring JdbcTemplate class and how to use it?</h3>
<p>Spring Framework provides excellent integration with JDBC API and provides JdbcTemplate utility class that we can use to avoid bolier-plate code from our database operations logic such as Opening/Closing Connection, ResultSet, PreparedStatement etc.</p>
<p>For JdbcTemplate example, please refer <a href="https://www.journaldev.com/2593/spring-jdbc-example" target="_blank" rel="noopener noreferrer">Spring JDBC Example</a>.</p>
</li>
<p><a name="spring-tomcat-jndi-DataSource"></a></p>
<li>
<h3>How to use Tomcat JNDI DataSource in Spring Web Application?</h3>
<p>For using servlet container configured JNDI DataSource, we need to configure it in the spring bean configuration file and then inject it to spring beans as dependencies. Then we can use it with <code>JdbcTemplate</code> to perform database operations.</p>
<p>Sample configuration would be:</p>
<pre><code>
&lt;beans:bean id="dbDataSource" class="org.springframework.jndi.JndiObjectFactoryBean"&gt;
    &lt;beans:property name="jndiName" value="java:comp/env/jdbc/MyLocalDB"/&gt;
&lt;/beans:bean&gt;
</code></pre>
<p>For complete example, please refer <a href="https://www.journaldev.com/2597/spring-datasource-jndi-with-tomcat-example" target="_blank" rel="noopener noreferrer">Spring Tomcat JNDI Example</a>.
</li>
<p><a name="spring-transaction-management"></a></p>
<li>
<h3>How would you achieve Transaction Management in Spring?</h3>
<p>Spring framework provides transaction management support through Declarative Transaction Management as well as programmatic transaction management. Declarative transaction management is most widely used because it&#8217;s easy to use and works in most of the cases.</p>
<p>We use annotate a method with <code>@Transactional</code> annotation for Declarative transaction management. We need to configure the transaction manager for the DataSource in the spring bean configuration file.</p>
<pre><code>
&lt;bean id="transactionManager"
    class="org.springframework.jdbc.datasource.DataSourceTransactionManager"&gt;
    &lt;property name="dataSource" ref="dataSource" /&gt;
&lt;/bean&gt;
</code></pre>
</li>
<p><a name="spring-DAO"></a></p>
<li>
<h3>What is Spring DAO?</h3>
<p>Spring DAO support is provided to work with data access technologies like JDBC, Hibernate in a consistent and easy way. For example we have <code>JdbcDaoSupport</code>, <code>HibernateDaoSupport</code>, <code>JdoDaoSupport</code> and <code>JpaDaoSupport</code> for respective technologies.</p>
<p>Spring DAO also provides consistency in exception hierarchy and we don&#8217;t need to catch specific exceptions.</p>
</li>
<p><a name="spring-hibernate-integration"></a></p>
<li>
<h3>How to integrate Spring and Hibernate Frameworks?</h3>
<p>We can use Spring ORM module to integrate Spring and Hibernate frameworks if you are using Hibernate 3+ where SessionFactory provides current session, then you should avoid using <code>HibernateTemplate</code> or <code>HibernateDaoSupport</code> classes and better to use DAO pattern with dependency injection for the integration.</p>
<p>Spring ORM provides support for using Spring declarative transaction management, so you should utilize that rather than going for Hibernate boiler-plate code for transaction management.</p>
<p>For better understanding you should go through following tutorials:</p>
<ul>
<li><a href="https://www.journaldev.com/3524/spring-hibernate-integration-example-tutorial" target="_blank" rel="noopener noreferrer">Spring Hibernate Integration Example</a></li>
<li><a href="https://www.journaldev.com/3531/spring-mvc-hibernate-mysql-integration-crud-example-tutorial" target="_blank" rel="noopener noreferrer">Spring MVC Hibernate Integration Example</a></li>
</ul>
</li>
<p><a name="spring-security"></a></p>
<li>
<h3>What is Spring Security?</h3>
<p>Spring security framework focuses on providing both authentication and authorization in java applications. It also takes care of most of the common security vulnerabilities such as CSRF attack.</p>
<p>It&#8217;s very beneficial and easy to use Spring security in web applications, through the use of annotations such as <code>@EnableWebSecurity</code>. You should go through the following posts to learn how to use the Spring Security framework.</p>
<ul>
<li><a href="https://www.journaldev.com/2715/spring-security-example-tutorial" target="_blank" rel="noopener noreferrer">Spring Security in Servlet Web Application</a></li>
<li><a href="https://www.journaldev.com/2736/spring-security-example-userdetailsservice" target="_blank" rel="noopener noreferrer">Spring MVC and Spring Security Integration Example</a></li>
</ul>
</li>
<p><a name="spring-properties-inject"></a></p>
<li>
<h3>How to inject a java.util.Properties into a Spring Bean?</h3>
<p>We need to define propertyConfigurer bean that will load the properties from the given property file. Then we can use Spring EL support to inject properties into other bean dependencies. For example;</p>
<pre><code>
&lt;bean id="propertyConfigurer" 
  class="org.springframework.context.support.PropertySourcesPlaceholderConfigurer"&gt;
    &lt;property name="location" value="/WEB-INF/application.properties" /&gt;
&lt;/bean&gt; 

&lt;bean class="com.journaldev.spring.EmployeeDaoImpl"&gt;
    &lt;property name="maxReadResults" value="${results.read.max}"/&gt;
&lt;/bean&gt;
</code></pre>
<p>If you are using annotation to configure the spring bean, then you can inject property like below.</p>
<pre><code>
@Value("${maxReadResults}") 
private int maxReadResults;
</code></pre>
</li>
<p><a name="spring-design-patterns"></a></p>
<li>
<h3>Name some of the design patterns used in Spring Framework?</h3>
<p>Spring Framework is using a lot of design patterns, some of the common ones are:</p>
<ol>
<li>Singleton Pattern: Creating beans with default scope.</li>
<li><a href="https://www.journaldev.com/1392/factory-design-pattern-in-java" target="_blank" rel="noopener noreferrer">Factory Pattern</a>: Bean Factory classes</li>
<li><a href="https://www.journaldev.com/1440/prototype-design-pattern-in-java" target="_blank" rel="noopener noreferrer">Prototype Pattern</a>: Bean scopes</li>
<li><a href="https://www.journaldev.com/1487/adapter-design-pattern-java" target="_blank" rel="noopener noreferrer">Adapter Pattern</a>: Spring Web and Spring MVC</li>
<li><a href="https://www.journaldev.com/1572/proxy-design-pattern" target="_blank" rel="noopener noreferrer">Proxy Pattern</a>: Spring Aspect Oriented Programming support</li>
<li><a href="https://www.journaldev.com/1763/template-method-design-pattern-in-java" target="_blank" rel="noopener noreferrer">Template Method Pattern</a>: JdbcTemplate, HibernateTemplate etc</li>
<li>Front Controller: Spring MVC DispatcherServlet</li>
<li>Data Access Object: Spring DAO support</li>
<li>Dependency Injection and Aspect Oriented Programming</li>
</ol>
</li>
<p><a name="spring-best-practices"></a></p>
<li>
<h3>What are some of the best practices for Spring Framework?</h3>
<p>Some of the best practices for Spring Framework are:</p>
<ol>
<li>Avoid version numbers in schema reference, to make sure we have the latest configs.</li>
<li>Divide spring bean configurations based on their concerns such as spring-jdbc.xml, spring-security.xml.</li>
<li>For spring beans that are used in multiple contexts in Spring MVC, create them in the root context and initialize with listener.</li>
<li>Configure bean dependencies as much as possible, try to avoid autowiring as much as possible.</li>
<li>For application-level properties, the best approach is to create a property file and read it in the spring bean configuration file.</li>
<li>For smaller applications, annotations are useful but for larger applications, annotations can become a pain. If we have all the configuration in XML files, maintaining it will be easier.</li>
<li>Use correct annotations for components for understanding the purpose easily. For services use @Service and for DAO beans use @Repository.</li>
<li>Spring framework has a lot of modules, use what you need. Remove all the extra dependencies that get usually added when you create projects through Spring Tool Suite templates.</li>
<li>If you are using Aspects, make sure to keep the join pint as narrow as possible to avoid advice on unwanted methods. Consider custom annotations that are easier to use and avoid any issues.</li>
<li>Use dependency injection when there is an actual benefit, just for the sake of loose-coupling don&#8217;t use it because it&#8217;s harder to maintain.</li>
</ol>
</li>
</ol>
<p>That&#8217;s all for Spring Framework interview questions. I hope these questions will help you in coming Java EE interview. I will keep on adding more questions to the list as soon as I found them. If you know some more questions that should be part of the list, make sure to add a comment for it and I will include it.<br />
 </p><div class='code-block code-block-6' style='margin: 8px auto; text-align: center; display: block; clear: both;'>
