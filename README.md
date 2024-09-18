
# 01 - Setup do LangFlow com Python

Este guia descreve o processo de instalação e execução do LangFlow diretamente em um ambiente Python. O LangFlow é uma ferramenta poderosa para a criação de fluxos de trabalho de IA, e aqui mostraremos como configurá-lo em um ambiente isolado.

## Comandos executados

### 1. Criar a pasta do Projeto:

Inicie criando uma pasta dedicada para o projeto e navegue até ela:

```bash
mkdir langflow
cd langflow
```

### 2. Iniciar ambiente virtual do Python

Crie e ative um ambiente virtual para isolar as dependências do Python:

```bash
# Criar ambiente virtual
python -m venv env

# Ativar o ambiente virtual
source env/bin/activate
```

> **Nota**: Em sistemas Windows, o comando para ativar o ambiente virtual é:
> ```bash
> .\env\Scripts\activate
> ```

### 3. Instalar o LangFlow

Com o ambiente virtual ativo, instale o LangFlow utilizando o `pip`. O argumento `-U` garante que a versão mais recente seja instalada:

```bash
python -m pip install langflow -U
```

### 4. Executar o LangFlow

Depois de instalar o LangFlow, você pode iniciar a ferramenta com o seguinte comando:

```bash
python -m langflow run
```

#### Saída esperada

Ao executar o comando acima, você verá uma saída semelhante à seguinte no terminal:

```bash
(env) ligerosmart@DESKTOP-KPHFMG7:~/langflow$ python -m langflow run  
Starting Langflow v1.0.18...  
╭───────────────────────────────────────────────────────────────────╮  
│ Welcome to ⛓ Langflow                                             │  
│                                                                   │  
│                                                                   │  
│ Collaborate, and contribute at our GitHub Repo 🌟                 │  
│                                                                   │  
│ We collect anonymous usage data to improve Langflow.              │  
│ You can opt-out by setting DO_NOT_TRACK=true in your environment. │  
│                                                                   │  
│ Access http://127.0.0.1:7861                                      │  
╰───────────────────────────────────────────────────────────────────╯
```

Isso executará o servidor LangFlow localmente, e você poderá acessá-lo no seu navegador através do endereço [http://127.0.0.1:7861](http://127.0.0.1:7861).


### Comandos adicionais

- Para desativar o ambiente virtual, use o comando:

```bash
deactivate
```

- Para parar o servidor LangFlow, basta utilizar `Ctrl+C` no terminal onde ele está rodando.

## Conclusão

Você agora tem um ambiente configurado para usar o LangFlow e pode começar a explorar a criação de fluxos de trabalho de IA! Se houver qualquer atualização ou mudança nas versões, é recomendável rodar novamente o comando `python -m pip install langflow -U` para garantir que a versão mais recente esteja sendo utilizada.
