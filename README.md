- 👋 Hi, I’m @javertus
- 👀 I’m interested in java.lang.ExceptionInInitializerError
Stacktrace:
sun.reflect.NativeConstructorAccessorImpl.newInstance0(Native Method)
sun.reflect.NativeConstructorAccessorImpl.newInstance(NativeConstructorAccessorImpl.java:62)
sun.reflect.DelegatingConstructorAccessorImpl.newInstance(DelegatingConstructorAccessorImpl.java:45)
java.lang.reflect.Constructor.newInstance(Constructor.java:423)
java.lang.Class.newInstance(Class.java:442)
org.openqa.selenium.support.PageFactory.instantiatePage(PageFactory.java:131)
org.openqa.selenium.support.PageFactory.initElements(PageFactory.java:112)
com.bahmni.gauge.common.PageFactory.getPage(PageFactory.java:47)
com.bahmni.gauge.common.specs.LoginSpec.navigateToLoginPage(LoginSpec.java:27)
sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
sun.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:43)
sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
java.lang.reflect.Method.invoke(Method.java:498)
com.thoughtworks.gauge.execution.MethodExecutor.execute(MethodExecutor.java:38)
com.thoughtworks.gauge.execution.StepExecutionStage.executeStepMethod(StepExecutionStage.java:132)
com.thoughtworks.gauge.execution.StepExecutionStage.execute(StepExecutionStage.java:86)
com.thoughtworks.gauge.execution.AbstractExecutionStage.execute(AbstractExecutionStage.java:67)
com.thoughtworks.gauge.execution.AbstractExecutionStage.executeNext(AbstractExecutionStage.java:24)
com.thoughtworks.gauge.execution.ExecutionPipeline.start(ExecutionPipeline.java:29)
com.thoughtworks.gauge.processor.ExecuteStepProcessor.process(ExecuteStepProcessor.java:39)
com.thoughtworks.gauge.connection.MessageDispatcher.dispatchMessages(MessageDispatcher.java:89)
com.thoughtworks.gauge.GaugeRuntime.runSpecs(GaugeRuntime.java:104)
com.thoughtworks.gauge.GaugeRuntime.access$100(GaugeRuntime.java:36)
com.thoughtworks.gauge.GaugeRuntime$2.run(GaugeRuntime.java:85)
java.lang.Thread.run(Thread.java:745)

<!---
javertus/javertus is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
