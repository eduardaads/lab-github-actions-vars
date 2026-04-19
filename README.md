1. Por que a Secret aparece como ***?
Porque o GitHub protege automaticamente valores sensíveis nos logs.
2. O deploy_app consegue ler BUILD_VERSION? Por quê?
3. Não. Porque cada job roda em um ambiente separado e variáveis não são compartilhadas entre jobs.
