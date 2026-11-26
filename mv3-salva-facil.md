# Política de Privacidade — MV3 Salva Fácil

**Vigência:** 26 de novembro de 2026.

A presente Política de Privacidade disciplina o tratamento de dados no âmbito da extensão MV3 Salva Fácil, desenvolvida por iniciativa própria de Diogo Toporcov e disponibilizada à MV3, doravante denominada “Extensão”. Seu objetivo é informar, de maneira transparente, as finalidades, condições e limites do tratamento de informações necessário à prestação de suas funcionalidades.

## 1. Objeto e âmbito de aplicação

A Extensão destina-se à geração de documentos PDF e ao salvamento de arquivos diretamente acessíveis pelo navegador, mediante API JavaScript, bem como à geração local de código para automatizar essas operações.

Esta Política aplica-se ao tratamento de informações realizado pela Extensão. O tratamento efetuado pelos sites visitados, pelo navegador, pelo sistema operacional ou por ferramentas de automação de terceiros está sujeito às respectivas políticas e condições de utilização.

## 2. Dados tratados e finalidades

A Extensão poderá acessar ou processar, na medida necessária à execução de suas funcionalidades:

- Endereço eletrônico (URL), título e identificadores da aba e do documento atual;
- Conteúdo textual e visual da página, incluindo elementos HTML, estilos, imagens e demais recursos necessários à renderização do PDF;
- Conteúdo binário de arquivos diretamente acessíveis, inclusive arquivos locais quando autorizado pelo navegador;
- Preferências de exportação, parâmetros de execução, nomes de arquivos e subpastas de destino;
- Identificadores, estados e informações operacionais de downloads, inclusive mensagens de erro.

A natureza das informações contidas nas páginas e nos arquivos depende do conteúdo acessado pelo usuário, podendo incluir dados pessoais, dados pessoais sensíveis ou informações de natureza profissional e empresarial. O tratamento desses dados limita-se à execução das operações de exportação, salvamento e retorno de seus resultados, bem como à gestão das preferências da Extensão.

A Extensão não exige a criação de conta própria, não solicita credenciais de autenticação e não mantém banco de dados de usuários ou histórico próprio de navegação.

## 3. Forma de processamento e permissões

A geração dos PDFs é realizada localmente pelo motor de impressão do navegador. As permissões de acesso a páginas, abas, depuração, execução de scripts, armazenamento local, navegação, downloads e processamento em documentos não visíveis são utilizadas para viabilizar a renderização, a validação do documento atual, a preparação dos arquivos e o respectivo salvamento.

A API JavaScript é disponibilizada no contexto das páginas em que o navegador permite sua execução. Consequentemente, os scripts das próprias páginas também podem invocar seus métodos públicos, consultar as configurações e receber informações operacionais sobre a execução. Não há distinção técnica entre chamadas realizadas pelo console e chamadas realizadas por scripts da página nesse contexto.

As operações de salvamento solicitadas por páginas são restritas à aba ativa e ao documento verificado, sujeitas à validação de parâmetros e a limites de concorrência e recursos. A API pública não disponibiliza comandos arbitrários de depuração, nem autoriza a sobrescrita de arquivos existentes ou a alteração persistente das configurações por scripts da página. Os resultados não incluem os bytes do PDF ou do arquivo salvo.

O acesso a arquivos locais depende da habilitação da respectiva permissão no navegador. A Extensão não se destina a contornar mecanismos de controle de acesso, gerenciamento corporativo ou proteção de conteúdo.

## 4. Armazenamento, conservação e eliminação

Durante a execução das operações, dados e arquivos poderão ser mantidos temporariamente em memória e em objetos binários locais (Blobs). Esses recursos são destinados exclusivamente ao processamento e são liberados após o uso, quando possível, ou mediante os mecanismos de expiração dos buffers temporários, configurados para dez minutos.

As preferências persistentes são armazenadas no perfil local do navegador, sem utilização de armazenamento em nuvem pela Extensão, e permanecem disponíveis até sua alteração, restauração ou remoção. Recomenda-se não inserir informações confidenciais nessas preferências, uma vez que as configurações podem ser consultadas pela API pública.

Os arquivos efetivamente salvos permanecem sob o controle do usuário, no diretório de downloads ou em suas subpastas. O navegador poderá conservar os respectivos registros de download conforme suas próprias configurações. A desinstalação da Extensão não implica a exclusão automática dos arquivos anteriormente baixados ou do histórico de downloads do navegador.

## 5. Compartilhamento de dados e serviços de terceiros

A Extensão não transmite documentos, conteúdo de páginas ou informações de navegação à MV3, ao desenvolvedor ou a servidores próprios de processamento. Não utiliza serviços externos de conversão de PDF, publicidade, ferramentas de análise comportamental ou telemetria.

Quando solicitado o download de um arquivo remoto, o navegador poderá efetuar uma requisição ao servidor de origem ou ao destino de seus redirecionamentos, utilizando os mecanismos de autenticação e sessão aplicáveis. Durante a renderização de uma página, seus próprios scripts e recursos também poderão efetuar requisições de rede. Tais comunicações são inerentes ao funcionamento do navegador e dos serviços acessados e não constituem envio dos PDFs gerados a um serviço de conversão da Extensão.

Os scripts da página podem receber as respostas da API pública, incluindo o nome do arquivo, o identificador e o estado do download, mensagens de erro e configurações consultadas. A Extensão não fornece a esses scripts o conteúdo binário do arquivo salvo como resultado da operação.

Não comercializamos dados de usuários, não os utilizamos para publicidade personalizada, avaliação de crédito ou formação de perfis comerciais e não os transferimos a corretores de dados, plataformas publicitárias ou outros intermediários para tais finalidades.

O uso das informações acessadas por meio das APIs do navegador observa a [Política de Dados do Usuário da Chrome Web Store](https://developer.chrome.com/docs/webstore/program-policies/user-data), inclusive seus [requisitos de Uso Limitado (Limited Use)](https://developer.chrome.com/docs/webstore/program-policies/limited-use).

## 6. Segurança da informação

A Extensão adota medidas técnicas destinadas a limitar o tratamento à sua finalidade, entre elas a validação de parâmetros, a verificação da identidade do documento, a limitação de operações simultâneas, a normalização de nomes de arquivos e a liberação de recursos temporários.

A segurança dos arquivos salvos e das informações presentes nas páginas depende também das condições do dispositivo, do perfil do navegador e dos sistemas utilizados. Recomenda-se utilizar a Extensão em ambientes confiáveis e salvar somente conteúdos aos quais o usuário esteja legitimamente autorizado a ter acesso e a conservar.

## 7. Direitos e controle do titular

Observada a legislação aplicável, em especial a Lei nº 13.709/2018 (Lei Geral de Proteção de Dados Pessoais — LGPD), o titular poderá solicitar informações e exercer os direitos previstos em lei, incluindo confirmação e acesso ao tratamento, correção, anonimização, bloqueio, eliminação, portabilidade, informações sobre compartilhamento, oposição e revogação do consentimento, quando cabíveis.

Considerando o caráter local do processamento, a MV3 e o desenvolvedor não dispõem, por meio da Extensão, de acesso remoto aos documentos, arquivos ou preferências armazenados no dispositivo do usuário. O usuário poderá gerenciar as permissões concedidas, restaurar as preferências, excluir os arquivos salvos e desinstalar a Extensão pelas ferramentas disponibilizadas pelo navegador e pelo sistema operacional.

As solicitações relativas à privacidade poderão ser encaminhadas ao contato indicado nesta Política. O titular também poderá recorrer à Autoridade Nacional de Proteção de Dados (ANPD), nos termos da legislação aplicável.

## 8. Alterações desta Política

Esta Política poderá ser atualizada em razão de modificações nas funcionalidades da Extensão, nas práticas de tratamento ou nas exigências legais e regulamentares aplicáveis. A versão vigente será disponibilizada no endereço de publicação da Política, com a indicação de sua data de vigência. Alterações relevantes nas práticas de tratamento serão comunicadas de forma adequada, observados os requisitos de transparência e autorização aplicáveis.

## 9. Contato

Para esclarecimentos, solicitações ou comunicações relacionadas à privacidade e à proteção de dados:

**MV3 — Diogo Toporcov**  
E-mail: [diogo.toporcov@mv3.com.br](mailto:diogo.toporcov@mv3.com.br)
