# JBehave Integration Example

### How to integrate

1. Add ReportPortal's story reporter
2. Add ReportPortal's view generator

```java
 return new MostUsefulConfiguration()             
            .useStoryReporterBuilder(new StoryReporterBuilder()               
                .withFormats(ReportPortalFormat.INSTANCE))
            .useViewGenerator(new ReportPortalViewGenerator());
```