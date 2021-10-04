1. What is a Tekton Trigger? What Tekton entities are required for this to work with our Pipeline?
- Tekton component that allows to detect and extract information from events.
- THe entities are: EventListener, Trigger, TriggerTemplate, TriggerBinding, ClusterTriggerBinding, Interceptor
2. Since we have not yet added GitHub commit hooks, how did you test your Trigger? We can curl the webhook
