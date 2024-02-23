## Demonstrações
![demo1](images/demo1.png)


## Comandos

### Ajuda
```
   !chatgpt help
```

| Parâmetros | Descrição|
| :--------- | :---------------------------------- |
| `1` | Mostre a página de ajuda sobre **!chatgpt help**. |
| `2` | Mostre a página de ajuda sobre **!chatgpt set**. |
| `3` | Mostre a página de ajuda sobre **!chatgpt info**. |
| `4` | Mostre a página de ajuda sobre **!chatgpt get**. |
| `5` | Mostre a página de ajuda sobre **!chatgpt credits**. |

### Set (define a configuração)
```
   !chatgpt set
```

| Parâmetros | Descrição | Subparâmetros |
| :--------- | :---------------------------------- | :----------- |
| `model` | Defina o modelo ChatGpt. | gpt-4 / gpt-3.5-turbo / Variantes
| `temperature` | Defina a temperatura do ChatGpt. | 0,0 - 2,0
| `name` | Defina o nome do ChatGpt. | (Nome de 16 caracteres)
| `aswner_all` | Defina o Aswner tudo. | Verdadeiro falso
| `require_tag` | Defina a tag necessária. | Verdadeiro falso

### Informações
```
   !chatgpt info
```

| Parâmetro | Descrição |
| :---------- | :--------- |
| Nenhum | Mostrar algumas informações sobre Bedrock ChatGpt |

### Get (mostra a configuração)
```
   !chatgpt get
```

| Parâmetros | Descrição |
| :--------- | :---------------------------------- |
| `modelo` | Mostra o modelo ChatGpt. |
| `temperatura` | Mostra a temperatura do ChatGpt. |
| `nome` | Mostra o nome do ChatGpt. |
| `aswner_all` | Mostra se Respode tudo. |
| `require_tag` | Mostre a tag . |

### Créditos
```
   !chatgpt credits
```

| Parâmetro | Descrição |
| :---------- | :--------- |
| Nenhum | Mostra os créditos pelo desenvolvimento do Bedrock ChatGpt! |



## Configurando
Para usar o ChatGpt é necessária uma chave OpenAi!

OpenAi possui uma versão gratuita com uso limitado! E uma versão paga com menos limitação!
Você pode obter sua chave em https://openai.com/
## Executando

### Executando no Windows:
No Windows é muito fácil de executar! Ele é executado como um programa normal, mas exigirá permissão de firewall e você precisará permitir acesso público e privado!

### Rodando em Linux/Termux (Proot funciona melhor!)

Para rodar no Linux você precisa executar dentro do diretório do programa e digitar no terminal:
```bash
./bedrock_chatgpt
```

## Conectando

Se você tentar conectar-se no Minecraft Windows e não funcionar, digite o seguinte comando no PowerShell como Admin:
```PowerShell
CheckNetIsolation LoopbackExempt -a -n="Microsoft.MinecraftUWP_8wekyb3d8bbwe"
```

## Problemas conhecidos

****Falha ao iniciar após fechar o servidor!****

****Talvez um começo preguiçoso na primeira partida!****
