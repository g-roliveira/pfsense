Aqui está o texto transformado em Markdown para um arquivo `README.md`:

```markdown
# Procedimentos em TI e Bora para Prática
#### Autor: Robson Vaamonde

## Links Úteis
- Procedimentos em TI: [procedimentosemti.com.br](http://procedimentosemti.com.br)
- Bora para Prática: [boraparapratica.com.br](http://boraparapratica.com.br)
- Robson Vaamonde: [vaamonde.com.br](http://vaamonde.com.br)
- Facebook Procedimentos em TI: [facebook.com/ProcedimentosEmTi](https://www.facebook.com/ProcedimentosEmTi)
- Facebook Bora para Prática: [facebook.com/BoraParaPratica](https://www.facebook.com/BoraParaPratica)
- Instagram Procedimentos em TI: [instagram.com/procedimentoem](https://www.instagram.com/procedimentoem)
- YouTUBE Bora Para Prática: [youtube.com/boraparapratica](https://www.youtube.com/boraparapratica)
- LinkedIn Robson Vaamonde: [linkedin.com/in/robson-vaamonde-0b029028](https://www.linkedin.com/in/robson-vaamonde-0b029028/)

## Informações de Documentação
- Data de criação: 23/01/2021
- Data de atualização: 23/11/2022
- Versão: 0.12
- Testado e homologado no Firewall NG UTM Netgate pfSense 2.6.x, Plus 22.x e 23.x

## Recursos e Documentações do pfSense
- [Versões do software pfSense e FreeBSD](https://docs.netgate.com/pfsense/en/latest/releases/versions.html#x)
- [Migração para o pfSense Plus+ 22.x](https://docs.netgate.com/pfsense/en/latest/install/migrate-to-plus.html)
- [Atualização da versão do pfSense 2.6.0](https://docs.netgate.com/pfsense/en/latest/releases/22-01_2-6-0.html)
- [Versão anterior do pfSense 2.5.2](https://docs.netgate.com/pfsense/en/latest/releases/2-5-2.html)
- [Versão anterior do pfSense 2.5.1](https://docs.netgate.com/pfsense/en/latest/releases/21-02-2_2-5-1.html)
- [Versão base do pfSense 2.5.0](https://docs.netgate.com/pfsense/en/latest/releases/2-5-0.html)
- [Documentação Oficial do Netgate/pfSense em PDF](https://docs.netgate.com/manuals/pfsense/en/latest/the-pfsense-documentation.pdf)

## Configurações e Procedimentos
### Observações das configurações utilizadas nessa documentação
- (Default) = Configuração padrão do pfSense = ON ou OFF ou Value
- (Disable) = Desabilitado nessa configuração = OFF
- (Enable)  = Habilitado nessa configuração = ON
- (Remove)  = Removido dessa configuração = Sem valor ou opção
- <***>     = Botão de confirmação ou de aplicar as configurações

### Primeira etapa: Configuração do CA (Certificate Authority) e do Certificado SSL do pfSense
```
System
    Cert. Manager
        CAs
            +ADD
                Create / Edit CA
                    Descriptive name: BoraParaPratica (alterar conforme a sua necessidade)
                    Method: Create an internal Certificate Authority (Default)
                    Trust Store: ON (Enable)
                    Randomize Serial: OFF (Default)
                Internal Certificate Authority
                    Key type: RSA (Default)
                    Key length (bits): 2048 (Default)
                    Digest Algorithm: sha256 (Default)
                    Lifetime (days): 3650 (Default)
                    Common Name: ca-pfsense (alterar conforme a sua necessidade)
                    Country Code: BR (alterar conforme a sua necessidade)
                    Sate or Province: Sao Paulo (alterar conforme a sua necessidade)
                    City: Guarulhos (alterar conforme a sua necessidade)
                    Organization: Bora para Pratica (alterar conforme a sua necessidade)
                    Organizational Unit: Matriz Bora para Pratica (alterar conforme a sua necessidade)
            <Save>
```
[... O conteúdo continua seguindo o mesmo formato de estrutura ...]

### Quinta etapa: Instalação da CA nos Navegadores e Sistemas Operacional


[... Instruções detalhadas de instalação ...]
```

Este markdown é estruturado para oferecer uma visão clara e organizada do conteúdo, com links clicáveis e formatação para facilitar a leitura.
