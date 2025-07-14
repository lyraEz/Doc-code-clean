# CodeCleaner Pro - Static Version

Versão completamente estática do CodeCleaner Pro que funciona 100% no navegador sem necessidade de servidor.

## Características

- **100% Client-Side**: Funciona inteiramente no navegador
- **Zero Dependencies**: Não requer servidor ou instalação
- **Processamento Local**: Seus arquivos nunca saem do seu computador
- **Suporte a ZIP**: Processa arquivos ZIP completos mantendo estrutura
- **Interface Moderna**: Design responsivo com animações suaves

## Linguagens Suportadas

- Python (.py)
- JavaScript/TypeScript (.js, .ts, .jsx, .tsx)
- HTML/CSS (.html, .css)
- Lua (.lua)
- Java (.java)
- C/C++ (.c, .cpp)
- PHP (.php)
- Ruby (.rb)
- Go (.go)
- Rust (.rs)
- Arquivos ZIP (.zip)

## O que é Removido

- **Logs**: console.log(), print(), System.out.println(), etc.
- **Comentários**: // comentários, /* blocos */, # python, etc.
- **Debug**: debugger, breakpoint(), pdb.set_trace(), etc.
- **Warnings**: console.warn(), logging.warning(), etc.
- **Linhas vazias**: Reduz espaçamento excessivo

## Instalação

1. Extraia os arquivos em qualquer servidor web
2. Abra index.html em um navegador
3. Pronto! Não há dependências ou configuração necessária

### Servidor Local (Opcional)

```bash
# Python
python -m http.server 8000

# Node.js
npx serve .

# PHP
php -S localhost:8000
```

## Tecnologias

- **HTML5**: Estrutura semântica moderna
- **CSS3**: Variáveis CSS, gradientes, animações
- **JavaScript ES6+**: Modules, async/await, classes
- **JSZip**: Processamento de arquivos ZIP

## Segurança

- Processamento 100% local
- Nenhum arquivo é enviado para servidores
- Código open-source auditável
- Funciona offline após carregamento inicial

## Estrutura

```
static-build/
├── index.html       # Interface principal
├── styles.css       # Estilos customizados
├── scripts.js       # Lógica de processamento
└── README.md        # Este arquivo
```

## Uso

1. Arraste arquivos ou clique para selecionar
2. Clique em "Processar Arquivos"
3. Aguarde o processamento local
4. Baixe o arquivo "clear.zip" com código limpo

## Compatibilidade

- Chrome 60+
- Firefox 55+
- Safari 11+
- Edge 79+

## Licença

MIT License - Uso livre para projetos pessoais e comerciais.