@Component
public class WebhookInitializer implements ApplicationRunner {
    
    @Override
    public void run(ApplicationArguments args) throws Exception {
        // 1. Send POST request to generate webhook
        // 2. Determine question from regNo
        // 3. Solve manually and prepare finalQuery
        // 4. Send POST to webhook with JWT
    }
}
