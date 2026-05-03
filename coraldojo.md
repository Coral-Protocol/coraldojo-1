```bash
npx coralos-dev@coraldojo server configure --config-profile=coraldojo
```

```bash
npm create koog@RC-1.1.0 -- my-cool-agent --agentName=my-cool-agent --packageName=com.example.agents.mycoolagent
```


Run the server
```bash
npx coralos-dev@coraldojo server start --config-profile=coraldojo -- --auth.keys=dev --registry.include-debug-agents=true --registry.localAgents=$(pwd)/my-cool-agent --registry.includeCoralHomeAgents=false
```

http://localhost:5555/ui/console

