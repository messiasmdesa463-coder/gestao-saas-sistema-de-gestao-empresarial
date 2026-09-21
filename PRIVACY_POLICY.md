# Política de Privacidade — GestãoSaaS

**Última atualização:** 21 de setembro de 2026

Esta política descreve, em termos gerais, como a implantação do GestãoSaaS
pode tratar informações durante o uso do sistema. A organização que operar uma
instância do sistema é responsável por definir a finalidade do tratamento, a
base legal, os prazos de retenção e os direitos aplicáveis aos titulares.

## Informações que podem ser tratadas

Dependendo dos módulos habilitados, o sistema pode armazenar dados de
identificação e contato de empresas, usuários e funcionários; credenciais e
perfis de acesso; dados de produtos e estoque; movimentações operacionais;
registros de tickets e mensagens; e informações técnicas necessárias à
autenticação, segurança e funcionamento da aplicação.

## Finalidades

As informações podem ser utilizadas para autenticar usuários, administrar
empresas e permissões, controlar produtos e estoque, acompanhar indicadores,
prestar suporte e manter a segurança e a disponibilidade do serviço.

## Armazenamento e compartilhamento

Os dados podem ser armazenados em infraestrutura configurada pela organização,
incluindo Firebase/Firestore ou banco MySQL no backend PHP. O acesso deve ser
limitado às pessoas autorizadas e aos prestadores necessários para operar a
infraestrutura. Não venda dados pessoais.

## Segurança e responsabilidade da implantação

A implantação deve configurar regras de acesso, segredos, backups, retenção e
monitoramento antes de uso em produção. Este repositório não fornece
credenciais padrão; o primeiro administrador deve ser configurado de forma
segura no ambiente da implantação.

As regras de acesso do Firestore exigem autenticação. Antes de publicar uma
instância, configure o Firebase Authentication e substitua as regras-base por
regras de autorização por usuário, empresa e perfil.

## Direitos e contato

Solicitações relacionadas a acesso, correção, exclusão ou informações sobre o
tratamento de dados devem ser encaminhadas à organização responsável pela
instância. Para suporte técnico ao projeto, escreva para
[suportesaasgestao@gmail.com](mailto:suportesaasgestao@gmail.com).

Esta é uma política-base para o repositório e não substitui a avaliação
jurídica ou a política específica da organização que operar o sistema.
