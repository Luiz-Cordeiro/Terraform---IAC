## Infraestrutura como código
- Trata-se da definição, por meio de códigos, do gerenciamento e provisão de infraestrutura. Arquivos de configuração são responsáveis por manter um ambiente de aplicações em diferentes contextos.
- Terraform: terraform é uma forma popular de IaC, disponível no GCP, Azure e AWS
- Environment drift: é um problema muito comum com ambientes que não contam com IaC, já que a cada deploy pode haver mudanças que necessitam de ajustes e o controle sobre o ambiente é perdido
- Snowflake environment: é uma consequência da ausência de IaC, na qual múltiplos usuários fazem mudanças no ambiente sem nenhum tipo de coordenação e consistência
- Com IaC é possível criar múltiplos tipos de ambientes para validar a qualidade de aplicações sob diferentes condições
