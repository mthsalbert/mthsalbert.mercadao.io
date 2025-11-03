# undefined

# Ordem de trabalho

## Campos

| Rótulo                                         | Nome de API                                   | Tipo      | Ajuda                                                                                                                                                                                                                                                                                                                                                                                                |
| ---------------------------------------------- | --------------------------------------------- | --------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ID da ordem de trabalho                        | Id                                            | id        | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| ID do proprietário                             | OwnerId                                       | reference | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Excluído                                       | IsDeleted                                     | boolean   | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Número da ordem de trabalho                    | WorkOrderNumber                               | string    | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Código ISO da moeda                            | CurrencyIsoCode                               | picklist  | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Data de criação                                | CreatedDate                                   | datetime  | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Criado pelo ID                                 | CreatedById                                   | reference | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Data da última modificação                     | LastModifiedDate                              | datetime  | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Última modificação pelo ID                     | LastModifiedById                              | reference | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Modstamp do sistema                            | SystemModstamp                                | datetime  | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Data da última visualização                    | LastViewedDate                                | datetime  | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Última data citada                             | LastReferencedDate                            | datetime  | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| ID da conta                                    | AccountId                                     | reference | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| ID do contato                                  | ContactId                                     | reference | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| ID do caso                                     | CaseId                                        | reference | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| ID do direito                                  | EntitlementId                                 | reference | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| ID de contrato de serviço                      | ServiceContractId                             | reference | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| ID do ativo                                    | AssetId                                       | reference | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Rua                                            | Street                                        | textarea  | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Cidade                                         | City                                          | string    | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Estado/Província                               | State                                         | string    | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| CEP                                            | PostalCode                                    | string    | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| País                                           | Country                                       | string    | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Latitude                                       | Latitude                                      | double    | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Longitude                                      | Longitude                                     | double    | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Precisão do geocódigo                          | GeocodeAccuracy                               | picklist  | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Endereço                                       | Address                                       | address   | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Descrição                                      | Description                                   | textarea  | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Abertura                                       | StartDate                                     | datetime  | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Encerramento                                   | EndDate                                       | datetime  | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Assunto                                        | Subject                                       | string    | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| ID de pedido de trabalho raiz                  | RootWorkOrderId                               | reference | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Status                                         | Status                                        | picklist  | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Prioridade                                     | Priority                                      | picklist  | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Imposto                                        | Tax                                           | currency  | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Subtotal                                       | Subtotal                                      | currency  | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Preço total                                    | TotalPrice                                    | currency  | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Item de linha                                  | LineItemCount                                 | int       | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| ID do catálogo de preços                       | Pricebook2Id                                  | reference | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Desconto                                       | Discount                                      | percent   | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Total geral                                    | GrandTotal                                    | currency  | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| ID de ordem de trabalho pai                    | ParentWorkOrderId                             | reference | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Fechado                                        | IsClosed                                      | boolean   | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Parado                                         | IsStopped                                     | boolean   | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Parado desde                                   | StopStartDate                                 | datetime  | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Hora de início da política do SLA              | SlaStartDate                                  | datetime  | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Hora de término da política do SLA             | SlaExitDate                                   | datetime  | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| ID do horário comercial                        | BusinessHoursId                               | reference | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Status do marco                                | MilestoneStatus                               | string    | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Duração                                        | Duration                                      | double    | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Tipo de duração                                | DurationType                                  | picklist  | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Duração em minutos                             | DurationInMinutes                             | double    | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Contagem do compromisso de serviço             | ServiceAppointmentCount                       | int       | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| ID do tipo de trabalho                         | WorkTypeId                                    | reference | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| ID de território                               | ServiceTerritoryId                            | reference | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Categoria do status                            | StatusCategory                                | picklist  | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| ID do Local                                    | LocationId                                    | reference | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| ID do plano de manutenção                      | MaintenancePlanId                             | reference | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Data de manutenção sugerida                    | SuggestedMaintenanceDate                      | date      | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Tamanho mínimo da equipe                       | MinimumCrewSize                               | int       | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Tamanho recomendado da equipe                  | RecommendedCrewSize                           | int       | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| ID do Layout do relatório de serviço           | ServiceReportTemplateId                       | reference | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| ID do item de linha do pedido de retorno       | ReturnOrderLineItemId                         | reference | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| ID do pedido de retorno                        | ReturnOrderId                                 | reference | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Gerado de plano de manutenção                  | IsGeneratedFromMaintenancePlan                | boolean   | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Idioma do relatório de serviço                 | ServiceReportLanguage                         | picklist  | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| ID da regra de trabalho de manutenção          | MaintenanceWorkRuleId                         | reference | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| ID da garantia do ativo                        | AssetWarrantyId                               | reference | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| ID da campanha de serviço do produto           | ProductServiceCampaignId                      | reference | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| ID do item de campanha de serviço do produto   | ProductServiceCampaignItemId                  | reference | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| ID do modelo de prompts do resumo pré-trabalho | PreWorkBriefPromptTemplate                    | string    | Insira o ID do modelo de prompts de Resumo pré-trabalho ativado. Para encontrar o ID, abra o modelo no Criador de prompts e copie os caracteres depois de "EinsteinPromptStudio/" do URL. Por exemplo, neste URL: https://testcom98.test1.my.pc-rnd.salesforce-setup.com/lightning/setup/EinsteinPromptStudio/0hfSG000001SUFVYA4/edit?c__versionId=3vNSG0000000g8v2AA, the ID is 0hfSG000001SUFVYA4. |
| Resumo pré-trabalho                            | PostWorkSummary                               | textarea  | Insira um resumo manualmente. Se você estiver usando o Agentforce, seu agente de IA poderá preencher o resumo para você.                                                                                                                                                                                                                                                                             |
| Prioridade de agendamento                      | FSL__Scheduling_Priority__c                   | double    | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| É preenchido em candidato                      | FSL__IsFillInCandidate__c                     | boolean   | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Evitar geocodificação para ações Chatter       | FSL__Prevent_Geocoding_For_Chatter_Actions__c | boolean   | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Horários de visitação                          | FSL__VisitingHours__c                         | reference | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Oportunidade                                   | Oportunidade__c                               | reference | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Tipo de ordem interna                          | DWTipoOrdemInterna__c                         | picklist  | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Data da entrega técnica                        | DWDataEntregaTecnica__c                       | date      | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Meio de contato para receber pesquisa          | DWMeioContatoReceberPesquisa__c               | picklist  | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Nível de satisfação com entrega técnica        | DWNivelSatisfacaoEntregaTecnica__c            | picklist  | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Box                                            | DWBox__c                                      | double    | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Aprovador                                      | DWAprovador__c                                | reference | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Status de aprovação de garantia                | StatusAprovacao__c                            | picklist  | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| O equipamento está                             | DWEquipamentoEsta__c                          | picklist  | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Qual problema/sintoma?                         | DWQualProblemaSintoma__c                      | textarea  | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Apresenta código de erro?                      | DWApresentaCodigoErro__c                      | boolean   | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Apresenta luz de advertência?                  | DWApresentaLuzAdvertencia__c                  | boolean   | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| O problema é:                                  | OProblemaE__c                                 | picklist  | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Em que condição o problema ocorre?             | DWEmQueCondicaProblemaOcorre__c               | string    | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Algo foi feito para resolver?                  | DWAlgoFeitoParaResolver__c                    | picklist  | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Descrição do código de erro                    | DWDescricaoCodigoErro__c                      | string    | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Tipo de ordem de trabalho                      | TipoOrdemTrabalho__c                          | picklist  | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Alerta violação auxiliar                       | AlertaViolacaoAuxiliar__c                     | picklist  | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Alerta de violação                             | DWAlertaViolacao__c                           | string    | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Revenda                                        | Revenda__c                                    | picklist  | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Situação                                       | Situacao__c                                   | picklist  | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Status integracao                              | StatusIntegracaoAtiva__c                      | picklist  | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Busca Produtos                                 | BuscaProdutos__c                              | boolean   | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Contato                                        | Contato__c                                    | string    | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Data de criação ERP                            | DTAEMISSAO__c                                 | datetime  | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| DTA_ENCERRAMENTO                               | DTAENCERRAMENTO__c                            | datetime  | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Código exclusivo                               | DWCodigoExclusivo__c                          | string    | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Revenda                                        | DWRevendaLocalizada__c                        | reference | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Data Agendamento                               | DataAgendamento__c                            | datetime  | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Empresa                                        | Empresa__c                                    | reference | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Número OS ERP(NRO_OS)                          | NROOS__c                                      | string    | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Busca Orçamento                                | BuscaOrcamento__c                             | boolean   | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Busca Servicos                                 | BuscaServicos__c                              | boolean   | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Fonte pagadora                                 | FontePagadora__c                              | picklist  | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Descrição da falha                             | DWDescricaoFalha__c                           | textarea  | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Amarração fiscal tipo de serviço               | AmarracaoFiscalTipoServico__c                 | picklist  | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Categoria fonte pagadora                       | CategoriaFontePagadora__c                     | picklist  | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Ocorrência de Garantia                         | DWNumeroOcorrencia__c                         | string    | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Tech Connect/Web                               | DWTechConnect__c                              | string    | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Chassi/Monobloco                               | DWChassiAtivo__c                              | string    | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| SET                                            | DWSET__c                                      | string    | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Modelo de plano de trabalho vinculado          | DWModeloPlanoTrabalhoVinculado__c             | boolean   | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Itens de linha da ordem                        | DWItensLinhaOrdem__c                          | double    | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Categoria OS                                   | CategoriaOS__c                                | picklist  | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Servico Externo                                | ServicoExterno__c                             | picklist  | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Servico Garantia                               | ServicoGarantia__c                            | picklist  | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Servico Interno                                | ServicoInterno__c                             | picklist  | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Servico Revisão                                | ServicoRevisao__c                             | picklist  | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Situacao OFI Solicitacao                       | SituacaoOFISolicitacao__c                     | picklist  | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Status Integração OFI Solicitacao              | StatusIntegracaoOFISolicitacao__c             | picklist  | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Código Exclusivo OFI Solicitacao               | CodigoExclusivoOFISolicitacao__c              | string    | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| KILOMETRAGEM                                   | KILOMETRAGEM__c                               | double    | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Nro Solicitacao                                | NROSolicitacao__c                             | double    | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Proximo Peca                                   | ProximaPeca__c                                | double    | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Proximo Servico                                | ProximoServico__c                             | double    | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Duração                                        | DWDuracao__c                                  | double    | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Horímetro                                      | DWHorimetro__c                                | double    | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Idade (dias)                                   | Idade__c                                      | double    | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Idade (escala)                                 | DWIdadeEscala__c                              | string    | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Marca do ativo                                 | MarcaAtivo__c                                 | string    | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Frota                                          | DWFrota__c                                    | string    | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Data de término da garantia                    | DWDataTerminoGarantia__c                      | date      | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Data de abertura                               | DWDataAbertura__c                             | date      | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Ultima integração                              | DWUltimaIntegracao__c                         | datetime  | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Quantidade de horas de serviço                 | DWQuantidadeHorasServico__c                   | double    | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Tipo Servico OS                                | TipoServicoOS__c                              | picklist  | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Forçar recálculo de duração?                   | DWForcarRecalculoDuracao__c                   | boolean   | Quando alternado para verdadeiro, o sistema irá apagar os compromissos de serviço (apenas se status for 'Nenhum') e criar novos de acordo com a duração (campo DWDuracao__c) dos itens de trabalhos.                                                                                                                                                                                                 |
| Documento de Aprovação do Cliente              | DocumentoAprovacaoCliente__c                  | string    | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Descrição do trabalho                          | DWDescricaoTrabalho__c                        | textarea  | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Criado SF                                      | DWCriadoSF__c                                 | boolean   | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Calcular sumarização de itens?                 | DWCalcularSumarizacaoItens__c                 | boolean   | Quando alternado para verdadeiro, a oportunidade relacionada terá a quantidade dos produtos correspondentes recalculada.                                                                                                                                                                                                                                                                             |
| Oportunidade criada                            | DWOportunidadeCriada__c                       | boolean   | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Aprovação do analista de garantia              | DWAprovacaoAnalistaGarantia__c                | picklist  | Utilizado para validação da abertura do processo de garantia quando a data está expirada ou vazia                                                                                                                                                                                                                                                                                                    |
| Aprovação do coordenador                       | DWAprovacaoCoordenador__c                     | picklist  | Utilizado para conferir o processo de garantia submetido ao fabricante                                                                                                                                                                                                                                                                                                                               |
| Cliente p/ emissão NF - Peças                  | DWClienteEmissaoNFPecas__c                    | reference | Cliente para emissão da NF - Peças (665)                                                                                                                                                                                                                                                                                                                                                             |
| Necessita aprovação de garantia                | DWNecessitaAprovacaoGarantia__c               | boolean   | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Analista de garantia de filial                 | DWAnalistaGarantiaFilial__c                   | reference | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Data/hora envio aprovação coordenador          | DWDataHoraEnvioAprovacaoCoordenador__c        | datetime  | Data e hora do envio do registro para o processo de aprovação de garantia submetido ao fabricante.                                                                                                                                                                                                                                                                                                   |
| Data/hora retorno aprovação coordenador        | DWDataHoraRetornoAprovacaoCoordenador__c      | datetime  | Data e hora do retorno do registro para o processo de aprovação de garantia submetido ao fabricante.                                                                                                                                                                                                                                                                                                 |
| Código da empresa                              | DWFormulaCodigoEmpresa__c                     | double    | -                                                                                                                                                                                                                                                                                                                                                                                                    |
| Cliente faturamento - Peças                    | DWClienteFaturamentoPecas__c                  | reference | Cliente faturamento - Peças (480)                                                                                                                                                                                                                                                                                                                                                                    |
| Cliente p/ emissão NF - Serviços               | DWClienteEmissaoNFServicos__c                 | reference | Cliente para emissão da NF                                                                                                                                                                                                                                                                                                                                                                           |
| Cliente faturamento - Serviços                 | DWClienteFaturamentoServicos__c               | reference | Cliente faturamento serviços (752)                                                                                                                                                                                                                                                                                                                                                                   |

## Relacionamentos Filhos

| Rótulo                                | Nome de relacionamento                | Campo de referência    | Objeto Relacionado                   |
| ------------------------------------- | ------------------------------------- | ---------------------- | ------------------------------------ |
| AIInsightValue                        | -                                     | SobjectLookupValueId   | AIInsightValue                       |
| AIRecordInsight                       | -                                     | TargetId               | AIRecordInsight                      |
| ActionPlans                           | ActionPlans                           | TargetId               | ActionPlan                           |
| ActionPlanChangeEvent                 | -                                     | TargetId               | ActionPlanChangeEvent                |
| ActivityHistories                     | ActivityHistories                     | WhatId                 | ActivityHistory                      |
| AgentWork                             | -                                     | WorkItemId             | AgentWork                            |
| AgentWorkChangeEvent                  | -                                     | WorkItemId             | AgentWorkChangeEvent                 |
| ApprovalSubmissions                   | ApprovalSubmissions                   | RelatedRecordId        | ApprovalSubmission                   |
| ApprovalWorkItems                     | ApprovalWorkItems                     | RelatedRecordId        | ApprovalWorkItem                     |
| AttachedContentDocuments              | AttachedContentDocuments              | LinkedEntityId         | AttachedContentDocument              |
| AttachedContentNotes                  | AttachedContentNotes                  | LinkedEntityId         | AttachedContentNote                  |
| Attachments                           | Attachments                           | ParentId               | Attachment                           |
| Casos__r                              | Casos__r                              | DWOrdemTrabalho__c     | Case                                 |
| CombinedAttachments                   | CombinedAttachments                   | ParentId               | CombinedAttachment                   |
| ContactRequests                       | ContactRequests                       | WhatId                 | ContactRequest                       |
| ContentDocumentLinks                  | ContentDocumentLinks                  | LinkedEntityId         | ContentDocumentLink                  |
| ContentDocumentLinkChangeEvent        | -                                     | LinkedEntityId         | ContentDocumentLinkChangeEvent       |
| ContentVersion                        | -                                     | FirstPublishLocationId | ContentVersion                       |
| ContentVersionChangeEvent             | -                                     | FirstPublishLocationId | ContentVersionChangeEvent            |
| Oportunidades_da_ordem_de_trabalho__r | Oportunidades_da_ordem_de_trabalho__r | OrdemTrabalho__c       | DWOportunidadeOrdemTrabalho__c       |
| DigitalSignatures                     | DigitalSignatures                     | ParentId               | DigitalSignature                     |
| DigitalSignatureChangeEvent           | -                                     | ParentId               | DigitalSignatureChangeEvent          |
| DynamicDataCaptures                   | DynamicDataCaptures                   | ParentRecordId         | DynamicDataCapture                   |
| Emails                                | Emails                                | RelatedToId            | EmailMessage                         |
| EmailMessageChangeEvent               | -                                     | RelatedToId            | EmailMessageChangeEvent              |
| EntityMilestones                      | EntityMilestones                      | ParentEntityId         | EntityMilestone                      |
| FeedSubscriptionsForEntity            | FeedSubscriptionsForEntity            | ParentId               | EntitySubscription                   |
| Events                                | Events                                | WhatId                 | Event                                |
| EventChangeEvent                      | -                                     | WhatId                 | EventChangeEvent                     |
| EventRelations                        | EventRelations                        | RelationId             | EventRelation                        |
| EventRelationChangeEvent              | -                                     | RelationId             | EventRelationChangeEvent             |
| Expenses                              | Expenses                              | WorkOrderId            | Expense                              |
| ExpenseChangeEvent                    | -                                     | WorkOrderId            | ExpenseChangeEvent                   |
| FeedComment                           | -                                     | ParentId               | FeedComment                          |
| FeedItem                              | -                                     | ParentId               | FeedItem                             |
| FlowExecutionErrorEvent               | -                                     | ContextRecordId        | FlowExecutionErrorEvent              |
| FlowOrchestrationWorkItems            | FlowOrchestrationWorkItems            | RelatedRecordId        | FlowOrchestrationWorkItem            |
| FlowRecordRelation                    | -                                     | RelatedRecordId        | FlowRecordRelation                   |
| Http_Request_Logs__r                  | Http_Request_Logs__r                  | OrdemTrabalho__c       | HttpRequestLog__c                    |
| LinkedArticles                        | LinkedArticles                        | LinkedEntityId         | LinkedArticle                        |
| LinkedArticleChangeEvent              | -                                     | LinkedEntityId         | LinkedArticleChangeEvent             |
| ParentEntities                        | ParentEntities                        | ParentEntityId         | NetworkActivityAudit                 |
| NetworkFeedResponseMetric             | -                                     | ParentRecordId         | NetworkFeedResponseMetric            |
| NetworkUserHistoryRecentToRecord      | NetworkUserHistoryRecentToRecord      | RecordId               | NetworkUserHistoryRecent             |
| Notes                                 | Notes                                 | ParentId               | Note                                 |
| NotesAndAttachments                   | NotesAndAttachments                   | ParentId               | NoteAndAttachment                    |
| OpenActivities                        | OpenActivities                        | WhatId                 | OpenActivity                         |
| Oportunidades__r                      | Oportunidades__r                      | OrdemTrabalho__c       | Opportunity                          |
| ProdutoOportunidade__r                | ProdutoOportunidade__r                | DWOrdemTrabalho__c     | OpportunityLineItem                  |
| OutgoingEmail                         | -                                     | RelatedToId            | OutgoingEmail                        |
| PendingServiceRouting                 | -                                     | WorkItemId             | PendingServiceRouting                |
| PendingServiceRoutingChangeEvent      | -                                     | WorkItemId             | PendingServiceRoutingChangeEvent     |
| PendingServiceRoutingInteractionInfo  | -                                     | PrimaryRecordId        | PendingServiceRoutingInteractionInfo |
| PendingServiceRoutingInteractionInfo  | -                                     | TargetObjectId         | PendingServiceRoutingInteractionInfo |
| ProcessInstances                      | ProcessInstances                      | TargetObjectId         | ProcessInstance                      |
| ProcessInstanceChangeEvent            | -                                     | TargetObjectId         | ProcessInstanceChangeEvent           |
| ProcessSteps                          | ProcessSteps                          | TargetObjectId         | ProcessInstanceHistory               |
| ProductsConsumed                      | ProductsConsumed                      | WorkOrderId            | ProductConsumed                      |
| ProductConsumedChangeEvent            | -                                     | WorkOrderId            | ProductConsumedChangeEvent           |
| ProductRequests                       | ProductRequests                       | WorkOrderId            | ProductRequest                       |
| ProductRequestChangeEvent             | -                                     | WorkOrderId            | ProductRequestChangeEvent            |
| ProductRequestLineItems               | ProductRequestLineItems               | WorkOrderId            | ProductRequestLineItem               |
| ProductRequestLineItemChangeEvent     | -                                     | WorkOrderId            | ProductRequestLineItemChangeEvent    |
| ProductsRequired                      | ProductsRequired                      | ParentRecordId         | ProductRequired                      |
| ProductRequiredChangeEvent            | -                                     | ParentRecordId         | ProductRequiredChangeEvent           |
| Quotes                                | Quotes                                | RelatedWorkId          | Quote                                |
| QuoteChangeEvent                      | -                                     | RelatedWorkId          | QuoteChangeEvent                     |
| RecordActions                         | RecordActions                         | RecordId               | RecordAction                         |
| RecordActionHistories                 | RecordActionHistories                 | ParentRecordId         | RecordActionHistory                  |
| ResourcePreferences                   | ResourcePreferences                   | RelatedRecordId        | ResourcePreference                   |
| ResourcePreferenceChangeEvent         | -                                     | RelatedRecordId        | ResourcePreferenceChangeEvent        |
| ServiceAppointments                   | ServiceAppointments                   | ParentRecordId         | ServiceAppointment                   |
| ServiceAppointmentChangeEvent         | -                                     | ParentRecordId         | ServiceAppointmentChangeEvent        |
| ServiceReports                        | ServiceReports                        | ParentId               | ServiceReport                        |
| ServiceReportChangeEvent              | -                                     | ParentId               | ServiceReportChangeEvent             |
| SkillRequirements                     | SkillRequirements                     | RelatedRecordId        | SkillRequirement                     |
| SkillRequirementChangeEvent           | -                                     | RelatedRecordId        | SkillRequirementChangeEvent          |
| SurveySubjectEntities                 | SurveySubjectEntities                 | SubjectId              | SurveySubject                        |
| SurveySubjectChangeEvent              | -                                     | SubjectId              | SurveySubjectChangeEvent             |
| Tasks                                 | Tasks                                 | WhatId                 | Task                                 |
| TaskChangeEvent                       | -                                     | WhatId                 | TaskChangeEvent                      |
| TaskRelations                         | TaskRelations                         | RelationId             | TaskRelation                         |
| TaskRelationChangeEvent               | -                                     | RelationId             | TaskRelationChangeEvent              |
| TimeSheetEntries                      | TimeSheetEntries                      | WorkOrderId            | TimeSheetEntry                       |
| TimeSheetEntryChangeEvent             | -                                     | WorkOrderId            | TimeSheetEntryChangeEvent            |
| TopicAssignments                      | TopicAssignments                      | EntityId               | TopicAssignment                      |
| ChildWorkOrders                       | ChildWorkOrders                       | ParentWorkOrderId      | WorkOrder                            |
| DescendantWorkOrders                  | DescendantWorkOrders                  | RootWorkOrderId        | WorkOrder                            |
| WorkOrderChangeEvent                  | -                                     | ParentWorkOrderId      | WorkOrderChangeEvent                 |
| WorkOrderChangeEvent                  | -                                     | RootWorkOrderId        | WorkOrderChangeEvent                 |
| Feeds                                 | Feeds                                 | ParentId               | WorkOrderFeed                        |
| Histories                             | Histories                             | WorkOrderId            | WorkOrderHistory                     |
| WorkOrderLineItems                    | WorkOrderLineItems                    | WorkOrderId            | WorkOrderLineItem                    |
| WorkOrderLineItemChangeEvent          | -                                     | WorkOrderId            | WorkOrderLineItemChangeEvent         |
| Shares                                | Shares                                | ParentId               | WorkOrderShare                       |
| NewWorkPlans                          | NewWorkPlans                          | ParentRecordId         | WorkPlan                             |
| WorkPlans                             | WorkPlans                             | WorkOrderId            | WorkPlan                             |
| WorkPlanChangeEvent                   | -                                     | ParentRecordId         | WorkPlanChangeEvent                  |
| WorkPlanChangeEvent                   | -                                     | WorkOrderId            | WorkPlanChangeEvent                  |
| NewWorkSteps                          | NewWorkSteps                          | ParentRecordId         | WorkStep                             |
| WorkSteps                             | WorkSteps                             | WorkOrderId            | WorkStep                             |
| WorkStepChangeEvent                   | -                                     | ParentRecordId         | WorkStepChangeEvent                  |
| WorkStepChangeEvent                   | -                                     | WorkOrderId            | WorkStepChangeEvent                  |

## Visualizações de Lista

### Valtra

Consulta: SELECT WorkOrderNumber, NROOS__c, toLabel(CategoriaFontePagadora__c), WorkType.Name, Account.Name, DWIdadeEscala__c, Asset.Name, DWChassiAtivo__c, MarcaAtivo__c, toLabel(Status), ServiceTerritory.Name, DTAEMISSAO__c, DWDuracao__c, CreatedDate, LastModifiedDate, Id, CurrencyIsoCode, SystemModstamp, WorkType.Id, WorkTypeId, Account.Id, AccountId, Account.RecordTypeId, Asset.Id, AssetId, ServiceTerritory.Id, ServiceTerritoryId FROM WorkOrder WHERE Asset.Name like '%9AGT2006KMM013207%' ORDER BY LastModifiedDate DESC NULLS LAST, Id DESC NULLS LAST

| Rótulo                      | Campo                     |
| --------------------------- | ------------------------- |
| Número da ordem de trabalho | WorkOrderNumber           |
| Número OS ERP(NRO_OS)       | NROOS__c                  |
| Categoria fonte pagadora    | CategoriaFontePagadora__c |
| Tipo de trabalho            | WorkType.Name             |
| Conta                       | Account.Name              |
| Idade (escala)              | DWIdadeEscala__c          |
| Ativo                       | Asset.Name                |
| Chassi/Monobloco            | DWChassiAtivo__c          |
| Marca do ativo              | MarcaAtivo__c             |
| Status                      | Status                    |
| Território de serviço       | ServiceTerritory.Name     |
| Data de criação ERP         | DTAEMISSAO__c             |
| Duração                     | DWDuracao__c              |
| Data de criação             | CreatedDate               |
| Data da última modificação  | LastModifiedDate          |
| ID da ordem de trabalho     | Id                        |
| Código ISO da moeda         | CurrencyIsoCode           |
| Modstamp do sistema         | SystemModstamp            |
| ID do tipo de trabalho      | WorkType.Id               |
| ID do tipo de trabalho      | WorkTypeId                |
| ID da conta                 | Account.Id                |
| ID da conta                 | AccountId                 |
| ID do tipo de registro      | Account.RecordTypeId      |
| ID do ativo                 | Asset.Id                  |
| ID do ativo                 | AssetId                   |
| ID de território            | ServiceTerritory.Id       |
| ID de território            | ServiceTerritoryId        |

### ERP sem Caso

Consulta: SELECT WorkOrderNumber, NROOS__c, Contato__c, Contact.Name, Account.Name, Asset.Name, DWChassiAtivo__c, toLabel(Status), CreatedDate, DTAEMISSAO__c, LastModifiedDate, DWUltimaIntegracao__c, Id, CurrencyIsoCode, SystemModstamp, Contact.Id, ContactId, Account.Id, AccountId, Account.RecordTypeId, Asset.Id, AssetId FROM WorkOrder WHERE NROOS__c != null AND Case.CaseNumber = null AND DTAEMISSAO__c >= 2025-01-02T03:00:00.000Z ORDER BY WorkOrderNumber ASC NULLS FIRST, Id ASC NULLS FIRST

| Rótulo                      | Campo                 |
| --------------------------- | --------------------- |
| Número da ordem de trabalho | WorkOrderNumber       |
| Número OS ERP(NRO_OS)       | NROOS__c              |
| Contato                     | Contato__c            |
| Contato                     | Contact.Name          |
| Conta                       | Account.Name          |
| Ativo                       | Asset.Name            |
| Chassi/Monobloco            | DWChassiAtivo__c      |
| Status                      | Status                |
| Data de criação             | CreatedDate           |
| Data de criação ERP         | DTAEMISSAO__c         |
| Data da última modificação  | LastModifiedDate      |
| Ultima integração           | DWUltimaIntegracao__c |
| ID da ordem de trabalho     | Id                    |
| Código ISO da moeda         | CurrencyIsoCode       |
| Modstamp do sistema         | SystemModstamp        |
| ID do contato               | Contact.Id            |
| ID do contato               | ContactId             |
| ID da conta                 | Account.Id            |
| ID da conta                 | AccountId             |
| ID do tipo de registro      | Account.RecordTypeId  |
| ID do ativo                 | Asset.Id              |
| ID do ativo                 | AssetId               |

### ERP

Consulta: SELECT WorkOrderNumber, NROOS__c, Contato__c, Contact.Name, Account.Name, Asset.Name, DWChassiAtivo__c, toLabel(Status), CreatedDate, DTAEMISSAO__c, LastModifiedDate, DWUltimaIntegracao__c, Id, CurrencyIsoCode, SystemModstamp, Contact.Id, ContactId, Account.Id, AccountId, Account.RecordTypeId, Asset.Id, AssetId FROM WorkOrder WHERE NROOS__c != null AND Case.CaseNumber != null ORDER BY WorkOrderNumber ASC NULLS FIRST, Id ASC NULLS FIRST

| Rótulo                      | Campo                 |
| --------------------------- | --------------------- |
| Número da ordem de trabalho | WorkOrderNumber       |
| Número OS ERP(NRO_OS)       | NROOS__c              |
| Contato                     | Contato__c            |
| Contato                     | Contact.Name          |
| Conta                       | Account.Name          |
| Ativo                       | Asset.Name            |
| Chassi/Monobloco            | DWChassiAtivo__c      |
| Status                      | Status                |
| Data de criação             | CreatedDate           |
| Data de criação ERP         | DTAEMISSAO__c         |
| Data da última modificação  | LastModifiedDate      |
| Ultima integração           | DWUltimaIntegracao__c |
| ID da ordem de trabalho     | Id                    |
| Código ISO da moeda         | CurrencyIsoCode       |
| Modstamp do sistema         | SystemModstamp        |
| ID do contato               | Contact.Id            |
| ID do contato               | ContactId             |
| ID da conta                 | Account.Id            |
| ID da conta                 | AccountId             |
| ID do tipo de registro      | Account.RecordTypeId  |
| ID do ativo                 | Asset.Id              |
| ID do ativo                 | AssetId               |

### Ordens de trabalho exibidas recentemente

Consulta: SELECT WorkOrderNumber, Subject, Account.Name, toLabel(Priority), toLabel(Status), Id, CurrencyIsoCode, CreatedDate, LastModifiedDate, SystemModstamp, Account.Id, AccountId, Account.RecordTypeId FROM WorkOrder USING SCOPE mru ORDER BY WorkOrderNumber ASC NULLS FIRST, Id ASC NULLS FIRST

| Rótulo                      | Campo                |
| --------------------------- | -------------------- |
| Número da ordem de trabalho | WorkOrderNumber      |
| Assunto                     | Subject              |
| Conta                       | Account.Name         |
| Prioridade                  | Priority             |
| Status                      | Status               |
| ID da ordem de trabalho     | Id                   |
| Código ISO da moeda         | CurrencyIsoCode      |
| Data de criação             | CreatedDate          |
| Data da última modificação  | LastModifiedDate     |
| Modstamp do sistema         | SystemModstamp       |
| ID da conta                 | Account.Id           |
| ID da conta                 | AccountId            |
| ID do tipo de registro      | Account.RecordTypeId |

### Abertas

Consulta: SELECT WorkOrderNumber, Account.Name, Asset.Name, DWChassiAtivo__c, toLabel(Status), toLabel(Priority), ServiceTerritory.Name, WorkType.Name, CreatedDate, DTAEMISSAO__c, Id, CurrencyIsoCode, LastModifiedDate, SystemModstamp, Account.Id, AccountId, Account.RecordTypeId, Asset.Id, AssetId, ServiceTerritory.Id, ServiceTerritoryId, WorkType.Id, WorkTypeId FROM WorkOrder WHERE Status != '9' ORDER BY WorkOrderNumber ASC NULLS FIRST, Id ASC NULLS FIRST

| Rótulo                      | Campo                 |
| --------------------------- | --------------------- |
| Número da ordem de trabalho | WorkOrderNumber       |
| Conta                       | Account.Name          |
| Ativo                       | Asset.Name            |
| Chassi/Monobloco            | DWChassiAtivo__c      |
| Status                      | Status                |
| Prioridade                  | Priority              |
| Território de serviço       | ServiceTerritory.Name |
| Tipo de trabalho            | WorkType.Name         |
| Data de criação             | CreatedDate           |
| Data de criação ERP         | DTAEMISSAO__c         |
| ID da ordem de trabalho     | Id                    |
| Código ISO da moeda         | CurrencyIsoCode       |
| Data da última modificação  | LastModifiedDate      |
| Modstamp do sistema         | SystemModstamp        |
| ID da conta                 | Account.Id            |
| ID da conta                 | AccountId             |
| ID do tipo de registro      | Account.RecordTypeId  |
| ID do ativo                 | Asset.Id              |
| ID do ativo                 | AssetId               |
| ID de território            | ServiceTerritory.Id   |
| ID de território            | ServiceTerritoryId    |
| ID do tipo de trabalho      | WorkType.Id           |
| ID do tipo de trabalho      | WorkTypeId            |

### Faturadas

Consulta: SELECT WorkOrderNumber, Account.Name, Asset.Name, DWChassiAtivo__c, toLabel(Status), toLabel(Priority), CreatedDate, DTAEMISSAO__c, Id, CurrencyIsoCode, LastModifiedDate, SystemModstamp, Account.Id, AccountId, Account.RecordTypeId, Asset.Id, AssetId FROM WorkOrder WHERE Status = '9' ORDER BY WorkOrderNumber ASC NULLS FIRST, Id ASC NULLS FIRST

| Rótulo                      | Campo                |
| --------------------------- | -------------------- |
| Número da ordem de trabalho | WorkOrderNumber      |
| Conta                       | Account.Name         |
| Ativo                       | Asset.Name           |
| Chassi/Monobloco            | DWChassiAtivo__c     |
| Status                      | Status               |
| Prioridade                  | Priority             |
| Data de criação             | CreatedDate          |
| Data de criação ERP         | DTAEMISSAO__c        |
| ID da ordem de trabalho     | Id                   |
| Código ISO da moeda         | CurrencyIsoCode      |
| Data da última modificação  | LastModifiedDate     |
| Modstamp do sistema         | SystemModstamp       |
| ID da conta                 | Account.Id           |
| ID da conta                 | AccountId            |
| ID do tipo de registro      | Account.RecordTypeId |
| ID do ativo                 | Asset.Id             |
| ID do ativo                 | AssetId              |

### 1 - Ordens com mais de 60 dias

Consulta: SELECT WorkOrderNumber, Account.Name, Asset.Name, DWChassiAtivo__c, toLabel(Status), toLabel(Priority), CreatedDate, DTAEMISSAO__c, Id, CurrencyIsoCode, LastModifiedDate, SystemModstamp, Account.Id, AccountId, Account.RecordTypeId, Asset.Id, AssetId FROM WorkOrder WHERE DTAEMISSAO__c < LAST_N_DAYS:60 AND Status != '9' ORDER BY WorkOrderNumber ASC NULLS FIRST, Id ASC NULLS FIRST

| Rótulo                      | Campo                |
| --------------------------- | -------------------- |
| Número da ordem de trabalho | WorkOrderNumber      |
| Conta                       | Account.Name         |
| Ativo                       | Asset.Name           |
| Chassi/Monobloco            | DWChassiAtivo__c     |
| Status                      | Status               |
| Prioridade                  | Priority             |
| Data de criação             | CreatedDate          |
| Data de criação ERP         | DTAEMISSAO__c        |
| ID da ordem de trabalho     | Id                   |
| Código ISO da moeda         | CurrencyIsoCode      |
| Data da última modificação  | LastModifiedDate     |
| Modstamp do sistema         | SystemModstamp       |
| ID da conta                 | Account.Id           |
| ID da conta                 | AccountId            |
| ID do tipo de registro      | Account.RecordTypeId |
| ID do ativo                 | Asset.Id             |
| ID do ativo                 | AssetId              |

### Abertos em garantia mais que 45 dias

Consulta: SELECT WorkOrderNumber, Account.Name, Asset.Name, DWChassiAtivo__c, toLabel(Status), toLabel(Priority), CreatedDate, DTAEMISSAO__c, Id, CurrencyIsoCode, LastModifiedDate, SystemModstamp, Account.Id, AccountId, Account.RecordTypeId, Asset.Id, AssetId FROM WorkOrder WHERE DTAEMISSAO__c < LAST_N_DAYS:5 AND CategoriaFontePagadora__c = '2' AND Status != '9' ORDER BY WorkOrderNumber ASC NULLS FIRST, Id ASC NULLS FIRST

| Rótulo                      | Campo                |
| --------------------------- | -------------------- |
| Número da ordem de trabalho | WorkOrderNumber      |
| Conta                       | Account.Name         |
| Ativo                       | Asset.Name           |
| Chassi/Monobloco            | DWChassiAtivo__c     |
| Status                      | Status               |
| Prioridade                  | Priority             |
| Data de criação             | CreatedDate          |
| Data de criação ERP         | DTAEMISSAO__c        |
| ID da ordem de trabalho     | Id                   |
| Código ISO da moeda         | CurrencyIsoCode      |
| Data da última modificação  | LastModifiedDate     |
| Modstamp do sistema         | SystemModstamp       |
| ID da conta                 | Account.Id           |
| ID da conta                 | AccountId            |
| ID do tipo de registro      | Account.RecordTypeId |
| ID do ativo                 | Asset.Id             |
| ID do ativo                 | AssetId              |

### Canceladas

Consulta: SELECT WorkOrderNumber, Account.Name, Asset.Name, DWChassiAtivo__c, toLabel(Status), toLabel(Priority), CreatedDate, DTAEMISSAO__c, Id, CurrencyIsoCode, LastModifiedDate, SystemModstamp, Account.Id, AccountId, Account.RecordTypeId, Asset.Id, AssetId FROM WorkOrder WHERE Status = '-1' ORDER BY WorkOrderNumber ASC NULLS FIRST, Id ASC NULLS FIRST

| Rótulo                      | Campo                |
| --------------------------- | -------------------- |
| Número da ordem de trabalho | WorkOrderNumber      |
| Conta                       | Account.Name         |
| Ativo                       | Asset.Name           |
| Chassi/Monobloco            | DWChassiAtivo__c     |
| Status                      | Status               |
| Prioridade                  | Priority             |
| Data de criação             | CreatedDate          |
| Data de criação ERP         | DTAEMISSAO__c        |
| ID da ordem de trabalho     | Id                   |
| Código ISO da moeda         | CurrencyIsoCode      |
| Data da última modificação  | LastModifiedDate     |
| Modstamp do sistema         | SystemModstamp       |
| ID da conta                 | Account.Id           |
| ID da conta                 | AccountId            |
| ID do tipo de registro      | Account.RecordTypeId |
| ID do ativo                 | Asset.Id             |
| ID do ativo                 | AssetId              |

### Minhas

Consulta: SELECT WorkOrderNumber, NROOS__c, Account.Name, Asset.Name, DWChassiAtivo__c, toLabel(Status), toLabel(Priority), CreatedDate, DTAEMISSAO__c, Pricebook2.Name, WorkType.Name, Id, CurrencyIsoCode, LastModifiedDate, SystemModstamp, Account.Id, AccountId, Account.RecordTypeId, Asset.Id, AssetId, Pricebook2.Id, Pricebook2Id, WorkType.Id, WorkTypeId FROM WorkOrder WHERE Status != '9' ORDER BY WorkOrderNumber ASC NULLS FIRST, Id ASC NULLS FIRST

| Rótulo                      | Campo                |
| --------------------------- | -------------------- |
| Número da ordem de trabalho | WorkOrderNumber      |
| Número OS ERP(NRO_OS)       | NROOS__c             |
| Conta                       | Account.Name         |
| Ativo                       | Asset.Name           |
| Chassi/Monobloco            | DWChassiAtivo__c     |
| Status                      | Status               |
| Prioridade                  | Priority             |
| Data de criação             | CreatedDate          |
| Data de criação ERP         | DTAEMISSAO__c        |
| Catálogo de preços          | Pricebook2.Name      |
| Tipo de trabalho            | WorkType.Name        |
| ID da ordem de trabalho     | Id                   |
| Código ISO da moeda         | CurrencyIsoCode      |
| Data da última modificação  | LastModifiedDate     |
| Modstamp do sistema         | SystemModstamp       |
| ID da conta                 | Account.Id           |
| ID da conta                 | AccountId            |
| ID do tipo de registro      | Account.RecordTypeId |
| ID do ativo                 | Asset.Id             |
| ID do ativo                 | AssetId              |
| ID do catálogo de preços    | Pricebook2.Id        |
| ID do catálogo de preços    | Pricebook2Id         |
| ID do tipo de trabalho      | WorkType.Id          |
| ID do tipo de trabalho      | WorkTypeId           |

### Abertas Valtra São José do Rio Preto

Consulta: SELECT WorkOrderNumber, NROOS__c, toLabel(CategoriaFontePagadora__c), WorkType.Name, Account.Name, DWIdadeEscala__c, Asset.Name, DWChassiAtivo__c, MarcaAtivo__c, toLabel(Status), ServiceTerritory.Name, CreatedDate, DTAEMISSAO__c, DWDuracao__c, Duration, Id, CurrencyIsoCode, LastModifiedDate, SystemModstamp, WorkType.Id, WorkTypeId, Account.Id, AccountId, Account.RecordTypeId, Asset.Id, AssetId, ServiceTerritory.Id, ServiceTerritoryId FROM WorkOrder WHERE Status != '9' AND Status != '7' AND (NOT MarcaAtivo__c like '%FENDT%') AND ServiceTerritory.Name = 'São José do Rio Preto' ORDER BY WorkOrderNumber ASC NULLS FIRST, Id ASC NULLS FIRST

| Rótulo                      | Campo                     |
| --------------------------- | ------------------------- |
| Número da ordem de trabalho | WorkOrderNumber           |
| Número OS ERP(NRO_OS)       | NROOS__c                  |
| Categoria fonte pagadora    | CategoriaFontePagadora__c |
| Tipo de trabalho            | WorkType.Name             |
| Conta                       | Account.Name              |
| Idade (escala)              | DWIdadeEscala__c          |
| Ativo                       | Asset.Name                |
| Chassi/Monobloco            | DWChassiAtivo__c          |
| Marca do ativo              | MarcaAtivo__c             |
| Status                      | Status                    |
| Território de serviço       | ServiceTerritory.Name     |
| Data de criação             | CreatedDate               |
| Data de criação ERP         | DTAEMISSAO__c             |
| Duração                     | DWDuracao__c              |
| Duração                     | Duration                  |
| ID da ordem de trabalho     | Id                        |
| Código ISO da moeda         | CurrencyIsoCode           |
| Data da última modificação  | LastModifiedDate          |
| Modstamp do sistema         | SystemModstamp            |
| ID do tipo de trabalho      | WorkType.Id               |
| ID do tipo de trabalho      | WorkTypeId                |
| ID da conta                 | Account.Id                |
| ID da conta                 | AccountId                 |
| ID do tipo de registro      | Account.RecordTypeId      |
| ID do ativo                 | Asset.Id                  |
| ID do ativo                 | AssetId                   |
| ID de território            | ServiceTerritory.Id       |
| ID de território            | ServiceTerritoryId        |

### Abertas Fendt São José do Rio Preto

Consulta: SELECT WorkOrderNumber, NROOS__c, DWTechConnect__c, DWNumeroOcorrencia__c, toLabel(CategoriaFontePagadora__c), WorkType.Name, DWIdadeEscala__c, Account.Name, DWChassiAtivo__c, Asset.Name, MarcaAtivo__c, CreatedDate, DTAEMISSAO__c, ServiceTerritory.Name, Case.CaseNumber, Id, CurrencyIsoCode, LastModifiedDate, SystemModstamp, WorkType.Id, WorkTypeId, Account.Id, AccountId, Account.RecordTypeId, Asset.Id, AssetId, ServiceTerritory.Id, ServiceTerritoryId, Case.Id, CaseId, Case.RecordTypeId FROM WorkOrder WHERE Status != '9' AND Status != '7' AND ServiceTerritory.Name like '%Agrolíder%' ORDER BY WorkOrderNumber ASC NULLS FIRST, Id ASC NULLS FIRST

| Rótulo                      | Campo                     |
| --------------------------- | ------------------------- |
| Número da ordem de trabalho | WorkOrderNumber           |
| Número OS ERP(NRO_OS)       | NROOS__c                  |
| Tech Connect/Web            | DWTechConnect__c          |
| Ocorrência de Garantia      | DWNumeroOcorrencia__c     |
| Categoria fonte pagadora    | CategoriaFontePagadora__c |
| Tipo de trabalho            | WorkType.Name             |
| Idade (escala)              | DWIdadeEscala__c          |
| Conta                       | Account.Name              |
| Chassi/Monobloco            | DWChassiAtivo__c          |
| Ativo                       | Asset.Name                |
| Marca do ativo              | MarcaAtivo__c             |
| Data de criação             | CreatedDate               |
| Data de criação ERP         | DTAEMISSAO__c             |
| Território de serviço       | ServiceTerritory.Name     |
| Caso                        | Case.CaseNumber           |
| ID da ordem de trabalho     | Id                        |
| Código ISO da moeda         | CurrencyIsoCode           |
| Data da última modificação  | LastModifiedDate          |
| Modstamp do sistema         | SystemModstamp            |
| ID do tipo de trabalho      | WorkType.Id               |
| ID do tipo de trabalho      | WorkTypeId                |
| ID da conta                 | Account.Id                |
| ID da conta                 | AccountId                 |
| ID do tipo de registro      | Account.RecordTypeId      |
| ID do ativo                 | Asset.Id                  |
| ID do ativo                 | AssetId                   |
| ID de território            | ServiceTerritory.Id       |
| ID de território            | ServiceTerritoryId        |
| ID do caso                  | Case.Id                   |
| ID do caso                  | CaseId                    |
| ID do tipo de registro      | Case.RecordTypeId         |

### Inicio2025

Consulta: SELECT WorkOrderNumber, Account.Name, Asset.Name, DWChassiAtivo__c, toLabel(Status), toLabel(Priority), Idade__c, DWIdadeEscala__c, CreatedDate, DWCodigoExclusivo__c, DTAEMISSAO__c, toLabel(TipoOrdemTrabalho__c), toLabel(CategoriaFontePagadora__c), LastModifiedDate, NROOS__c, Id, CurrencyIsoCode, SystemModstamp, Account.Id, AccountId, Account.RecordTypeId, Asset.Id, AssetId FROM WorkOrder WHERE DTAEMISSAO__c >= 2025-01-02T03:00:00.000Z ORDER BY WorkOrderNumber ASC NULLS FIRST, Id ASC NULLS FIRST

| Rótulo                      | Campo                     |
| --------------------------- | ------------------------- |
| Número da ordem de trabalho | WorkOrderNumber           |
| Conta                       | Account.Name              |
| Ativo                       | Asset.Name                |
| Chassi/Monobloco            | DWChassiAtivo__c          |
| Status                      | Status                    |
| Prioridade                  | Priority                  |
| Idade (dias)                | Idade__c                  |
| Idade (escala)              | DWIdadeEscala__c          |
| Data de criação             | CreatedDate               |
| Código exclusivo            | DWCodigoExclusivo__c      |
| Data de criação ERP         | DTAEMISSAO__c             |
| Tipo de ordem de trabalho   | TipoOrdemTrabalho__c      |
| Categoria fonte pagadora    | CategoriaFontePagadora__c |
| Data da última modificação  | LastModifiedDate          |
| Número OS ERP(NRO_OS)       | NROOS__c                  |
| ID da ordem de trabalho     | Id                        |
| Código ISO da moeda         | CurrencyIsoCode           |
| Modstamp do sistema         | SystemModstamp            |
| ID da conta                 | Account.Id                |
| ID da conta                 | AccountId                 |
| ID do tipo de registro      | Account.RecordTypeId      |
| ID do ativo                 | Asset.Id                  |
| ID do ativo                 | AssetId                   |

### Fendt São José do Rio Preto

Consulta: SELECT WorkOrderNumber, NROOS__c, DWTechConnect__c, DWNumeroOcorrencia__c, toLabel(CategoriaFontePagadora__c), WorkType.Name, DWIdadeEscala__c, Account.Name, DWChassiAtivo__c, Asset.Name, MarcaAtivo__c, CreatedDate, DTAEMISSAO__c, ServiceTerritory.Name, toLabel(Status), Id, CurrencyIsoCode, LastModifiedDate, SystemModstamp, WorkType.Id, WorkTypeId, Account.Id, AccountId, Account.RecordTypeId, Asset.Id, AssetId, ServiceTerritory.Id, ServiceTerritoryId FROM WorkOrder WHERE Status != '9' AND Status != '7' AND MarcaAtivo__c like '%Fendt%' ORDER BY WorkOrderNumber ASC NULLS FIRST, Id ASC NULLS FIRST

| Rótulo                      | Campo                     |
| --------------------------- | ------------------------- |
| Número da ordem de trabalho | WorkOrderNumber           |
| Número OS ERP(NRO_OS)       | NROOS__c                  |
| Tech Connect/Web            | DWTechConnect__c          |
| Ocorrência de Garantia      | DWNumeroOcorrencia__c     |
| Categoria fonte pagadora    | CategoriaFontePagadora__c |
| Tipo de trabalho            | WorkType.Name             |
| Idade (escala)              | DWIdadeEscala__c          |
| Conta                       | Account.Name              |
| Chassi/Monobloco            | DWChassiAtivo__c          |
| Ativo                       | Asset.Name                |
| Marca do ativo              | MarcaAtivo__c             |
| Data de criação             | CreatedDate               |
| Data de criação ERP         | DTAEMISSAO__c             |
| Território de serviço       | ServiceTerritory.Name     |
| Status                      | Status                    |
| ID da ordem de trabalho     | Id                        |
| Código ISO da moeda         | CurrencyIsoCode           |
| Data da última modificação  | LastModifiedDate          |
| Modstamp do sistema         | SystemModstamp            |
| ID do tipo de trabalho      | WorkType.Id               |
| ID do tipo de trabalho      | WorkTypeId                |
| ID da conta                 | Account.Id                |
| ID da conta                 | AccountId                 |
| ID do tipo de registro      | Account.RecordTypeId      |
| ID do ativo                 | Asset.Id                  |
| ID do ativo                 | AssetId                   |
| ID de território            | ServiceTerritory.Id       |
| ID de território            | ServiceTerritoryId        |

### Ordens com ERP

Consulta: SELECT WorkOrderNumber, NROOS__c, Contato__c, Contact.Name, Account.Name, Asset.Name, DWChassiAtivo__c, toLabel(Status), CreatedDate, DTAEMISSAO__c, LastModifiedDate, DWUltimaIntegracao__c, Id, CurrencyIsoCode, SystemModstamp, Contact.Id, ContactId, Account.Id, AccountId, Account.RecordTypeId, Asset.Id, AssetId FROM WorkOrder WHERE NROOS__c != null ORDER BY WorkOrderNumber ASC NULLS FIRST, Id ASC NULLS FIRST

| Rótulo                      | Campo                 |
| --------------------------- | --------------------- |
| Número da ordem de trabalho | WorkOrderNumber       |
| Número OS ERP(NRO_OS)       | NROOS__c              |
| Contato                     | Contato__c            |
| Contato                     | Contact.Name          |
| Conta                       | Account.Name          |
| Ativo                       | Asset.Name            |
| Chassi/Monobloco            | DWChassiAtivo__c      |
| Status                      | Status                |
| Data de criação             | CreatedDate           |
| Data de criação ERP         | DTAEMISSAO__c         |
| Data da última modificação  | LastModifiedDate      |
| Ultima integração           | DWUltimaIntegracao__c |
| ID da ordem de trabalho     | Id                    |
| Código ISO da moeda         | CurrencyIsoCode       |
| Modstamp do sistema         | SystemModstamp        |
| ID do contato               | Contact.Id            |
| ID do contato               | ContactId             |
| ID da conta                 | Account.Id            |
| ID da conta                 | AccountId             |
| ID do tipo de registro      | Account.RecordTypeId  |
| ID do ativo                 | Asset.Id              |
| ID do ativo                 | AssetId               |

### Garantias Abertas Fendt

Consulta: SELECT WorkOrderNumber, NROOS__c, DWTechConnect__c, DWNumeroOcorrencia__c, toLabel(CategoriaFontePagadora__c), WorkType.Name, DWIdadeEscala__c, Account.Name, DWChassiAtivo__c, Asset.Name, CreatedDate, DTAEMISSAO__c, ServiceTerritory.Name, Case.CaseNumber, Id, CurrencyIsoCode, LastModifiedDate, SystemModstamp, WorkType.Id, WorkTypeId, Account.Id, AccountId, Account.RecordTypeId, Asset.Id, AssetId, ServiceTerritory.Id, ServiceTerritoryId, Case.Id, CaseId, Case.RecordTypeId FROM WorkOrder WHERE Status != '9' AND Status != '7' AND ServiceTerritory.Name like '%Agrolíder%' AND CategoriaFontePagadora__c = '2' ORDER BY WorkOrderNumber ASC NULLS FIRST, Id ASC NULLS FIRST

| Rótulo                      | Campo                     |
| --------------------------- | ------------------------- |
| Número da ordem de trabalho | WorkOrderNumber           |
| Número OS ERP(NRO_OS)       | NROOS__c                  |
| Tech Connect/Web            | DWTechConnect__c          |
| Ocorrência de Garantia      | DWNumeroOcorrencia__c     |
| Categoria fonte pagadora    | CategoriaFontePagadora__c |
| Tipo de trabalho            | WorkType.Name             |
| Idade (escala)              | DWIdadeEscala__c          |
| Conta                       | Account.Name              |
| Chassi/Monobloco            | DWChassiAtivo__c          |
| Ativo                       | Asset.Name                |
| Data de criação             | CreatedDate               |
| Data de criação ERP         | DTAEMISSAO__c             |
| Território de serviço       | ServiceTerritory.Name     |
| Caso                        | Case.CaseNumber           |
| ID da ordem de trabalho     | Id                        |
| Código ISO da moeda         | CurrencyIsoCode           |
| Data da última modificação  | LastModifiedDate          |
| Modstamp do sistema         | SystemModstamp            |
| ID do tipo de trabalho      | WorkType.Id               |
| ID do tipo de trabalho      | WorkTypeId                |
| ID da conta                 | Account.Id                |
| ID da conta                 | AccountId                 |
| ID do tipo de registro      | Account.RecordTypeId      |
| ID do ativo                 | Asset.Id                  |
| ID do ativo                 | AssetId                   |
| ID de território            | ServiceTerritory.Id       |
| ID de território            | ServiceTerritoryId        |
| ID do caso                  | Case.Id                   |
| ID do caso                  | CaseId                    |
| ID do tipo de registro      | Case.RecordTypeId         |

### Todas

Consulta: SELECT WorkOrderNumber, NROOS__c, toLabel(CategoriaFontePagadora__c), WorkType.Name, Account.Name, DWIdadeEscala__c, Asset.Name, DWChassiAtivo__c, MarcaAtivo__c, toLabel(Status), ServiceTerritory.Name, DTAEMISSAO__c, DWDuracao__c, CreatedDate, LastModifiedDate, Id, CurrencyIsoCode, SystemModstamp, WorkType.Id, WorkTypeId, Account.Id, AccountId, Account.RecordTypeId, Asset.Id, AssetId, ServiceTerritory.Id, ServiceTerritoryId FROM WorkOrder ORDER BY CreatedDate DESC NULLS LAST, Id DESC NULLS LAST

| Rótulo                      | Campo                     |
| --------------------------- | ------------------------- |
| Número da ordem de trabalho | WorkOrderNumber           |
| Número OS ERP(NRO_OS)       | NROOS__c                  |
| Categoria fonte pagadora    | CategoriaFontePagadora__c |
| Tipo de trabalho            | WorkType.Name             |
| Conta                       | Account.Name              |
| Idade (escala)              | DWIdadeEscala__c          |
| Ativo                       | Asset.Name                |
| Chassi/Monobloco            | DWChassiAtivo__c          |
| Marca do ativo              | MarcaAtivo__c             |
| Status                      | Status                    |
| Território de serviço       | ServiceTerritory.Name     |
| Data de criação ERP         | DTAEMISSAO__c             |
| Duração                     | DWDuracao__c              |
| Data de criação             | CreatedDate               |
| Data da última modificação  | LastModifiedDate          |
| ID da ordem de trabalho     | Id                        |
| Código ISO da moeda         | CurrencyIsoCode           |
| Modstamp do sistema         | SystemModstamp            |
| ID do tipo de trabalho      | WorkType.Id               |
| ID do tipo de trabalho      | WorkTypeId                |
| ID da conta                 | Account.Id                |
| ID da conta                 | AccountId                 |
| ID do tipo de registro      | Account.RecordTypeId      |
| ID do ativo                 | Asset.Id                  |
| ID do ativo                 | AssetId                   |
| ID de território            | ServiceTerritory.Id       |
| ID de território            | ServiceTerritoryId        |

## Acionadores de Fluxo

### Atualiza campos do apollo conforme escolha do tipo de serviço

Atualiza campos do apollo conforme escolha do tipo de serviço {!$Flow.CurrentDateTime}

| Tipo de acionador | Tipo de registro |
| ----------------- | ---------------- |
| RecordAfterSave   | CreateAndUpdate  |

### DW - Before Flow - Work Order (Status)

DW - {!$Flow.CurrentDateTime}

| Tipo de acionador | Tipo de registro |
| ----------------- | ---------------- |
| RecordBeforeSave  | Update           |

### DW - Atribuir catálogo de preços na ORDEM DE TRABALHO

Este fluxo faz o campo CATÁLOGO DE PREÇOS ficar pré-preenchido

| Tipo de acionador | Tipo de registro |
| ----------------- | ---------------- |
| RecordAfterSave   | Create           |

### DW - Atribuir marco Ordem de trabalho

DW - Atribuir marco Ordem de trabalho {!$Flow.CurrentDateTime}

| Tipo de acionador | Tipo de registro |
| ----------------- | ---------------- |
| RecordAfterSave   | CreateAndUpdate  |

### DW - Atualizar o campo ORDEM DE TRABALHO

DW - Atualizar o campo ORDEM DE TRABALHO {!$Flow.CurrentDateTime}

| Tipo de acionador | Tipo de registro |
| ----------------- | ---------------- |
| RecordAfterSave   | Update           |

### OBSOLETO DW Chamar integração Ordem Trabalho

DW Chamar integração Ordem Trabalho {!$Flow.CurrentDateTime}

| Tipo de acionador | Tipo de registro |
| ----------------- | ---------------- |
| RecordAfterSave   | Create           |

### DW | Criação de tarefas recorrentes de relacionamento com cliente

A partir da OT fechada e a data de entrega técnica preenchida, são criadas tarefas para os respectivos responsáveis.

| Tipo de acionador | Tipo de registro |
| ----------------- | ---------------- |
| RecordAfterSave   | Update           |

### DW - Insere item de linha da ordem qdo há produtos no modelo de plano de trabalho

Se houver produtos relacionados ao modelo de plano de trabalho, eles irão para o item de linha da ordem de trabalho relacionada.

| Tipo de acionador | Tipo de registro |
| ----------------- | ---------------- |
| RecordAfterSave   | Update           |

### DW - OT - Atribui prop da opp como aprovador na OT

DW - OT - Atribui prop da opp como aprovador na OT {!$Flow.CurrentDateTime}

| Tipo de acionador | Tipo de registro |
| ----------------- | ---------------- |
| RecordAfterSave   | CreateAndUpdate  |

### DW - OT - Criar oportunidade

DW - OT - Criar oportunidade {!$Flow.CurrentDateTime}

| Tipo de acionador | Tipo de registro |
| ----------------- | ---------------- |
| RecordAfterSave   | CreateAndUpdate  |

### DW - OT - Preenche modelo relatorio de serviço

DW - OT - Preenche modelo relatorio de serviço {!$Flow.CurrentDateTime}

| Tipo de acionador | Tipo de registro |
| ----------------- | ---------------- |
| RecordAfterSave   | CreateAndUpdate  |

### DW - OT - Quando é criada, atualiza status do caso

DW - OT - Quando é criada, atualiza status do caso {!$Flow.CurrentDateTime}

| Tipo de acionador | Tipo de registro |
| ----------------- | ---------------- |
| RecordAfterSave   | Create           |

### DW - Ordem de trabalho - After flow - Dividir compromisso

Matheus Alberti 01/07/2025: Quando a ordem de trabalho é criado com duração maior que 8h, deve ser distribuído em outros compromissos de modo que a duração máxima de cada uma seja 8h. 
Matheus Alberti 16/07/2025: Quando território é alterado, o recalculo acontece também.

Matheus Alberti 02/07/2025: Quando o forçar recalculo for alterado para verdadeiro é um gatilho também.

| Tipo de acionador | Tipo de registro |
| ----------------- | ---------------- |
| RecordAfterSave   | CreateAndUpdate  |

### DW - Ordem de trabalho - Definir status de aprovação do analista

DW - Ordem de trabalho - Definir status de aprovação do analista {!$Flow.CurrentDateTime}

| Tipo de acionador | Tipo de registro |
| ----------------- | ---------------- |
| RecordAfterSave   | Create           |

### DW - Ordem de trabalho - Definir tipo de OS

DW - Ordem de trabalho - Definir tipo de OS {!$Flow.CurrentDateTime}

| Tipo de acionador | Tipo de registro |
| ----------------- | ---------------- |
| RecordAfterSave   | CreateAndUpdate  |

### DW - Ordem de trabalho - Deixar itens como integração pendente

DW - Ordem de trabalho - Deixar itens como integração pendente {!$Flow.CurrentDateTime}

| Tipo de acionador | Tipo de registro |
| ----------------- | ---------------- |
| RecordAfterSave   | Update           |

### DW - Ordem de trabalho - Enviar para aprovação coordenador

DW - Ordem de trabalho - Enviar para aprovação coordenador {!$Flow.CurrentDateTime}

| Tipo de acionador | Tipo de registro |
| ----------------- | ---------------- |
| RecordAfterSave   | CreateAndUpdate  |

### DW - Ordem de trabalho - Enviar para aprovação itens fora de garantia

DW - Ordem de trabalho - Enviar para aprovação itens fora de garantia {!$Flow.CurrentDateTime}

| Tipo de acionador | Tipo de registro |
| ----------------- | ---------------- |
| RecordAfterSave   | CreateAndUpdate  |

### DW - Ordem de trabalho - Gerar planos de trabalho

DW - Ordem de trabalho - Gerar planos de trabalho {!$Flow.CurrentDateTime}

| Tipo de acionador | Tipo de registro |
| ----------------- | ---------------- |
| RecordAfterSave   | Create           |

### DW - Ordem de trabalho - Integrar caso quando atualizar Nº OS

DW - Ordem de trabalho - Integrar caso quando atualizar Nº OS {!$Flow.CurrentDateTime}

| Tipo de acionador | Tipo de registro |
| ----------------- | ---------------- |
| RecordAfterSave   | Update           |

### DW - Ordem de trabalho - Integrar itens

DW - Ordem de trabalho - Integrar itens {!$Flow.CurrentDateTime}

| Tipo de acionador | Tipo de registro |
| ----------------- | ---------------- |
| RecordAfterSave   | Update           |

### DW - Ordem de trabalho - Solicitar número da OS de fábrica para analista

DW - Ordem de trabalho - Solicitar número da OS de fábrica para analista {!$Flow.CurrentDateTime}

| Tipo de acionador | Tipo de registro |
| ----------------- | ---------------- |
| RecordAfterSave   | Update           |

### DW - Ordem de trabalho - Sumarizar quantidade de itens da ordem de trabalho

DW - Ordem de trabalho - Sumarizar quantidade de itens da ordem de trabalho {!$Flow.CurrentDateTime}

| Tipo de acionador | Tipo de registro |
| ----------------- | ---------------- |
| RecordAfterSave   | Update           |

### DW - Ordem de trabalho - Zerar alocação quando encerrada

DW - Ordem de trabalho - Zerar alocação quando encerrada {!$Flow.CurrentDateTime}

| Tipo de acionador | Tipo de registro |
| ----------------- | ---------------- |
| RecordAfterSave   | Update           |

### DW - Ordem de trabalho - Zerar alocações

DW - Ordem de trabalho - Zerar alocações {!$Flow.CurrentDateTime}

| Tipo de acionador | Tipo de registro |
| ----------------- | ---------------- |
| RecordAfterSave   | Update           |

### DW - Ordem de trabalho - Fecha caso relacionado

Fecha caso relacionado quando OT mudar para 'aguardando faturamento'

| Tipo de acionador | Tipo de registro |
| ----------------- | ---------------- |
| RecordAfterSave   | Update           |

### DW - Ordem de trabalho - Inclui o catalogo padrao

DW - Ordem de trabalho - Inclui o catalogo {!$Flow.CurrentDateTime}

| Tipo de acionador | Tipo de registro |
| ----------------- | ---------------- |
| RecordAfterSave   | Create           |

### DW - Ordem de trabalho - Não criar 2 OT na mesma box

DW - Ordem de trabalho - Não criar 2 OT na mesma box {!$Flow.CurrentDateTime}

| Tipo de acionador | Tipo de registro |
| ----------------- | ---------------- |
| RecordBeforeSave  | CreateAndUpdate  |

### DW - Ordem de trabalho - Preenche categoria fonte pagadora

De acordo com tipo de ordem de trabalho

| Tipo de acionador | Tipo de registro |
| ----------------- | ---------------- |
| RecordAfterSave   | CreateAndUpdate  |

### DW - Scheduled - Atualizar ordem de trabalho para recalculo duração

Matheus Alberti: Força o recalculo para as ordens de produção com serviços vinculados.

| Tipo de acionador | Tipo de registro |
| ----------------- | ---------------- |
| Scheduled         | -                |

## Ações Rápidas

| Rótulo                           | Nome de API                                |
| -------------------------------- | ------------------------------------------ |
| Reservar compromisso             | FSL__Book_Appointment                      |
| Candidatos                       | FSL__Candidates                            |
| Caso de devolução                | Caso_de_devolucao                          |
| Contato                          | Contato                                    |
| Criar Caso - Serviço             | CriarCasoServico                           |
| Cliente                          | DWCliente                                  |
| Compromisso                      | DWCompromisso                              |
| Vender Peça(s)                   | DWVenderPeca                               |
| Emergência                       | FSL__Emergency                             |
| Iniciar atendimento              | InciarAtendimento                          |
| Nova conta                       | NewAccount                                 |
| Novo contato                     | NewContact                                 |
| Novo compromisso                 | FSL__NewEvent                              |
| Novo compromisso                 | NewEvent                                   |
| Novo grupo                       | NewGroup                                   |
| Nova oportunidade                | NewOpportunity                             |
| Novo caso                        | NovoCasoServicos                           |
| Novo caso - Serviços             | Novo_caso_servicos                         |
| Email                            | SendEmail                                  |
| Adicionar item de linha da ordem | WorkOrder.Adicionar_item_de_linha_da_ordem |
| Buscar Serviços do ERP           | WorkOrder.BuscarServicos                   |
| Buscar Orçamentos ERP            | WorkOrder.Buscar_Orcamentos_ERP            |
| Criar Oportunidade               | WorkOrder.CriarOportunidade                |
| Criar oportunidade               | WorkOrder.Criar_oportunidade               |
| Criar OT filha                   | WorkOrder.Criar_OT_filha                   |
| Buscar Produtos do ERP           | WorkOrder.DWBuscarProdutos                 |
| Recalcular duração               | WorkOrder.DWRecalcularDuracao              |
| Integrar Frente Caixa            | WorkOrder.IntegrarFrenteCaixa              |
| Integrar OFI Ordem Servico       | WorkOrder.IntegrarOFIOrdemServico          |
| Integrar OFI Solicitacao         | WorkOrder.IntegrarOFISolicitacao           |
| Integrar                         | WorkOrder.IntegrarOrdemTrabalho            |
| Email                            | WorkOrder.SendEmail                        |
| Publicar                         | FeedItem.TextPost                          |
| Arquivo                          | FeedItem.ContentPost                       |
| Ações inteligentes móveis        | FeedItem.MobileSmartActions                |
| Agradecimento                    | FeedItem.RypplePost                        |
| Link                             | FeedItem.LinkPost                          |
| Pesquisa                         | FeedItem.PollPost                          |
| Pergunta                         | FeedItem.QuestionPost                      |
| Nova nota                        | FeedItem.ContentNote                       |
| Nova cotação                     | WorkOrder._NewQuote                        |

## Acionadores Apex

### TR022_WorkOrder_AfterInsert

Status: Active

| Uso                 | Ativo |
| ------------------- | ----- |
| Antes de Inserir    | Não   |
| Depois de Inserir   | Sim   |
| Antes de Atualizar  | Não   |
| Depois de Atualizar | Não   |
| Antes de Excluir    | Não   |
| Depois de Excluir   | Não   |
| Depois de Recuperar | Não   |

### TR022_WorkOrder_AfterUpdate

Status: Active

| Uso                 | Ativo |
| ------------------- | ----- |
| Antes de Inserir    | Não   |
| Depois de Inserir   | Não   |
| Antes de Atualizar  | Não   |
| Depois de Atualizar | Sim   |
| Antes de Excluir    | Não   |
| Depois de Excluir   | Não   |
| Depois de Recuperar | Não   |

### TR022_WorkOrder_BeforeInsert

Status: Active

| Uso                 | Ativo |
| ------------------- | ----- |
| Antes de Inserir    | Sim   |
| Depois de Inserir   | Não   |
| Antes de Atualizar  | Não   |
| Depois de Atualizar | Não   |
| Antes de Excluir    | Não   |
| Depois de Excluir   | Não   |
| Depois de Recuperar | Não   |

### TR022_WorkOrder_BeforeUpdate

Status: Active

| Uso                 | Ativo |
| ------------------- | ----- |
| Antes de Inserir    | Não   |
| Depois de Inserir   | Não   |
| Antes de Atualizar  | Sim   |
| Depois de Atualizar | Não   |
| Antes de Excluir    | Não   |
| Depois de Excluir   | Não   |
| Depois de Recuperar | Não   |

### WorkOrderTrigger

Status: Inactive

Resumo IA: Aciona método após inserir ou atualizar WorkOrder, delegando lógica para handler que automatiza processos e mantém dados sincronizados.

| Uso                 | Ativo |
| ------------------- | ----- |
| Antes de Inserir    | Não   |
| Depois de Inserir   | Sim   |
| Antes de Atualizar  | Não   |
| Depois de Atualizar | Sim   |
| Antes de Excluir    | Não   |
| Depois de Excluir   | Não   |
| Depois de Recuperar | Não   |

# Oportunidade

## Campos

| Rótulo                                   | Nome de API                            | Tipo      | Ajuda                                                                                                                                                                                                                                                                                                                                                                                  |
| ---------------------------------------- | -------------------------------------- | --------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ID da oportunidade                       | Id                                     | id        | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Excluído                                 | IsDeleted                              | boolean   | -                                                                                                                                                                                                                                                                                                                                                                                      |
| ID da conta                              | AccountId                              | reference | -                                                                                                                                                                                                                                                                                                                                                                                      |
| ID do tipo de registro                   | RecordTypeId                           | reference | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Particular                               | IsPrivate                              | boolean   | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Nome                                     | Name                                   | string    | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Descrição                                | Description                            | textarea  | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Fase                                     | StageName                              | picklist  | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Valor                                    | Amount                                 | currency  | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Probabilidade (%)                        | Probability                            | percent   | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Valor esperado                           | ExpectedRevenue                        | currency  | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Quantidade                               | TotalOpportunityQuantity               | double    | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Data de fechamento                       | CloseDate                              | date      | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Tipo de oportunidade                     | Type                                   | picklist  | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Próxima etapa                            | NextStep                               | string    | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Origem do lead                           | LeadSource                             | picklist  | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Fechado                                  | IsClosed                               | boolean   | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Ganhos                                   | IsWon                                  | boolean   | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Categoria de previsão                    | ForecastCategory                       | picklist  | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Categoria de previsão                    | ForecastCategoryName                   | picklist  | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Moeda da oportunidade                    | CurrencyIsoCode                        | picklist  | -                                                                                                                                                                                                                                                                                                                                                                                      |
| ID da campanha                           | CampaignId                             | reference | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Tem item                                 | HasOpportunityLineItem                 | boolean   | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Está dividido                            | IsSplit                                | boolean   | -                                                                                                                                                                                                                                                                                                                                                                                      |
| ID do catálogo de preços                 | Pricebook2Id                           | reference | -                                                                                                                                                                                                                                                                                                                                                                                      |
| ID do proprietário                       | OwnerId                                | reference | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Data de criação                          | CreatedDate                            | datetime  | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Duração                                  | AgeInDays                              | int       | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Criado pelo ID                           | CreatedById                            | reference | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Data da última modificação               | LastModifiedDate                       | datetime  | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Última modificação pelo ID               | LastModifiedById                       | reference | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Modstamp do sistema                      | SystemModstamp                         | datetime  | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Última atividade                         | LastActivityDate                       | date      | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Atividade recente                        | LastActivityInDays                     | int       | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Contagem de push                         | PushCount                              | int       | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Data da última mudança de fase           | LastStageChangeDate                    | datetime  | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Dias em Fase                             | LastStageChangeInDays                  | int       | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Trimestre fiscal                         | FiscalQuarter                          | int       | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Ano fiscal                               | FiscalYear                             | int       | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Período fiscal                           | Fiscal                                 | string    | -                                                                                                                                                                                                                                                                                                                                                                                      |
| ID do contato                            | ContactId                              | reference | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Data da última visualização              | LastViewedDate                         | datetime  | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Última data citada                       | LastReferencedDate                     | datetime  | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Id de Cotação                            | SyncedQuoteId                          | reference | -                                                                                                                                                                                                                                                                                                                                                                                      |
| ID do contrato                           | ContractId                             | reference | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Possui uma atividade aberta              | HasOpenActivity                        | boolean   | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Possui uma tarefa atrasada               | HasOverdueTask                         | boolean   | -                                                                                                                                                                                                                                                                                                                                                                                      |
| ID do histórico de oportunidades         | LastAmountChangedHistoryId             | reference | -                                                                                                                                                                                                                                                                                                                                                                                      |
| ID do histórico de oportunidades         | LastCloseDateChangedHistoryId          | reference | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Importante                               | IsPriorityRecord                       | boolean   | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Budget Confirmed                         | Budget_Confirmed__c                    | boolean   | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Discovery Completed                      | Discovery_Completed__c                 | boolean   | -                                                                                                                                                                                                                                                                                                                                                                                      |
| ROI Analysis Completed                   | ROI_Analysis_Completed__c              | boolean   | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Itens que requerem análise               | DW_NOX__ItensRequeremAnalise__c        | double    | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Loss Reason                              | Loss_Reason__c                         | picklist  | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Quantidade reservada                     | DW_NOX__QuantidadeReservada__c         | double    | Toda quantidade reservada para produtos dessa oportunidade.                                                                                                                                                                                                                                                                                                                            |
| Data da clonagem                         | DW_SPT__DataClonagem__c                | date      | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Oportunidade clonada                     | DW_SPT__OportunidadeClonada__c         | boolean   | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Oportunidade principal                   | DW_SPT__OportunidadePrincipal__c       | reference | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Alerta aprovações                        | DWAlertaAprova__c                      | string    | Verde = "Aprovado" ou "Não necessário".  / Amarelo = "Em aprovação". /  Vermelho = "Rejeita" ou "Necessário" .                                                                                                                                                                                                                                                                         |
| Forma de pagamento                       | DWFormaPagamento__c                    | picklist  | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Influência do frete no preço             | DWInfluenciaFretePreco__c              | picklist  | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Motivo do fechamento                     | DWMotivoFechamento__c                  | picklist  | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Período do dia solicitado para entrega   | DWPeriodoDiaSolicitadoParaEntrega__c   | picklist  | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Status da aprovação comercial            | DWStatusAprovacaoComercial__c          | picklist  | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Status da aprovação financeira           | DWStatusAprovacaoFinanceira__c         | picklist  | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Status da aprovação logística            | DWStatusAprovacaoLogistica__c          | picklist  | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Tipo de documento de vendas              | DWTipoDocumentoVendas__c               | picklist  | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Tipo de frete                            | DWTipoFrete__c                         | picklist  | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Nº de cotações                           | DWNumeroCotacoes__c                    | double    | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Quantidade de itens                      | DWQuantidadeItens__c                   | double    | Contagem de produtos da oportunidade.                                                                                                                                                                                                                                                                                                                                                  |
| Aprovador financeiro                     | DWAprovadorFinanceiro__c               | reference | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Aprovador logística                      | DWAprovadorLogistica__c                | reference | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Codigo da opp                            | DWCodigoOpp__c                         | string    | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Condição de pagamento                    | DWCondicaoPagamento__c                 | reference | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Cotação de frete (filial de faturamento) | DWCotacaoFreteFilialFaturamento__c     | reference | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Cotação de frete (filial de produção)    | DWCotacaoFreteFilialProducao__c        | reference | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Custo (filial fat. até destino)          | DWCustoFilialFatAteDestino__c          | currency  | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Custo (filial prd. até destino)          | DWCustoFilialPrdAteDestino__c          | currency  | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Custo (filial prd. até filial fat.)      | DWCustoFilialPrdAteFilialFat__c        | currency  | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Data solicitada para emissão da NF       | DWDataSolicitadaEmissaoNF__c           | date      | Informe a data em que o cliente solicitou a emissão da Nota Fiscal. Esse campo é crucial para garantir que a documentação fiscal seja emitida dentro do prazo esperado, facilitando o processo de faturamento e entrega                                                                                                                                                                |
| Data solicitada para entrega             | DWDataSolicitadaEntrega__c             | date      | Insira a data em que o cliente solicitou a entrega do produto ou serviço. Esse campo ajuda a garantir que as expectativas do cliente sejam atendidas e permite o acompanhamento adequado do processo de entrega                                                                                                                                                                        |
| Descrição do motivo/perda                | DWDescricaoMotivoPerda__c              | string    | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Distância (filial fat. até destino)      | DWDistanciaFilialFatAteDestino__c      | double    | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Distância (filial prd. até destino)      | DWDistanciaFilialPrdAteDestino__c      | double    | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Distância (filial prd. até filial fat.)  | DWDistanciaFilialPrdAteFilialFat__c    | double    | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Endereço pré-definido                    | DWEnderecoPreDefinido__c               | reference | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Filial de faturamento                    | DWFilialFaturamento__c                 | reference | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Filial de produção                       | DWFilialProducao__c                    | reference | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Margem                                   | DWMargem__c                            | percent   | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Outras observações                       | DWOutrasObservacoes__c                 | string    | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Outros custos (filial fat. até destino)  | DWOutrosCustosFilialFatAteDestino__c   | currency  | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Outros custos (filial prd. até destino)  | DWOutrosCustosFilialPrdAteDestino__c   | currency  | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Outros custos (fil. prd. até fil. fat.)  | DWOutrosCustosFilialPrdAteFilialFat__c | currency  | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Pedido de compra                         | DWPedidoCompra__c                      | string    | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Transportadora                           | DWTransportadora__c                    | reference | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Valor frete                              | DWValorFrete__c                        | currency  | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Bairro de entrega                        | DW_AddressBairroEntrega__c             | string    | -                                                                                                                                                                                                                                                                                                                                                                                      |
| CEP ou código postal de entrega          | DW_AddressCEPEntrega__c                | string    | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Cidade de entrega                        | DW_AddressCidadeEntrega__c             | string    | Cidade, município ou distrito de entrega.                                                                                                                                                                                                                                                                                                                                              |
| Complemento de entrega                   | DW_AddressComplementoEntrega__c        | string    | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Estado de entrega                        | DW_AddressEstadoEntrega__c             | string    | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Número de entrega                        | DW_AddressNumeroEntrega__c             | string    | -                                                                                                                                                                                                                                                                                                                                                                                      |
| País de entrega                          | DW_AddressPaisEntrega__c               | string    | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Rua de entrega                           | DW_AddressRuaEntrega__c                | string    | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Tipo de logradouro de entrega            | DW_AddressTipoLogradouroEntrega__c     | string    | Exemplos: Rua, Avenida, Praça, Travessa, Alameda, Estrada, Boulevard, Largo, Rodovia, etc.                                                                                                                                                                                                                                                                                             |
| Código do município de entrega (IBGE)    | DW_CodigoMunicipioEntregaIBGE__c       | string    | Esse código é único para cada município e serve como uma referência padronizada em todo o país. Geralmente, ele é composto por um conjunto de números que identificam o estado e o município específico. Por exemplo, o código do IBGE para o município de São Paulo é 3550308, onde "35" é o código do estado de São Paulo e "50308" é o código específico do município de São Paulo. |
| Pedido de origem                         | PedidoOrigem__c                        | reference | Quando a oportunidade for criada a partir do pedido, ou seja, quando o campo DWReplicarParaOportunidade__c em Order for igual a verdadeiro, esse campo é alimentado com id do pedido de origem.                                                                                                                                                                                        |
| contagemVisualizacoes                    | contagemVisualizacoes__c               | double    | -                                                                                                                                                                                                                                                                                                                                                                                      |
| primeiraVisualizacao                     | primeiraVisualizacao__c                | datetime  | -                                                                                                                                                                                                                                                                                                                                                                                      |
| ultimaVisualizacao                       | ultimaVisualizacao__c                  | datetime  | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Nome da condição de pagamento            | DWNomeCondicaoPagamento__c             | string    | Usado na geração da proposta, não deve ser usado para outros fins.                                                                                                                                                                                                                                                                                                                     |
| Nome da transportadora                   | DWNomeTransportadora__c                | string    | Usado na geração da proposta, não deve ser usado para outros fins.                                                                                                                                                                                                                                                                                                                     |
| Prazo médio da condição de pagamento     | DWPrazoMedioCondicaoPagamento__c       | double    | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Peso total (em quilos)                   | DWPesoTotalQuilos__c                   | double    | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Ativo                                    | Ativo__c                               | reference | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Empresa                                  | Empresa__c                             | picklist  | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Situação OS                              | Situacao__c                            | picklist  | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Código exclusivo                         | CodigoExclusivo__c                     | string    | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Contato                                  | Contato__c                             | string    | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Revenda                                  | DWRevendaLocalizada__c                 | reference | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Ordem de trabalho                        | OrdemTrabalho__c                       | reference | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Franquia                                 | Franquia__c                            | picklist  | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Caso                                     | Caso__c                                | reference | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Data do pagamento                        | DWDataPagamento__c                     | date      | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Número da solicitação do cliente         | DWNumeroSolicitacaoCliente__c          | string    | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Empresa                                  | DWEmpresa__c                           | reference | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Tipo de transação                        | DWTipoTransacao__c                     | picklist  | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Código fiscal                            | DWCodigoFiscal__c                      | picklist  | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Aprovador N1 de peças                    | DWAprovadorN1__c                       | reference | Informação atribuída automaticamente. Gerente do usuário proprietário da oportunidade.                                                                                                                                                                                                                                                                                                 |
| Aprovador N2 de peças                    | DWAprovadorN2__c                       | reference | Informação atribuída automaticamente. Gerente do gerente do usuário proprietário da oportunidade.                                                                                                                                                                                                                                                                                      |
| Quantidade de itens para aprovação n1    | QuantidadeItensAprovacaoN1__c          | double    | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Quantidade de itens para aprovação n2    | DWQuantidadeItensAprovacaoN2__c        | double    | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Status do cálculo horizontal             | DW_NPX__StatusCalculoHorizontal__c     | picklist  | Campo de controle que aciona o cálculo horizontal quando atribuído para 'Pendente'.                                                                                                                                                                                                                                                                                                    |
| Situação VEI Proposta                    | SituacaoVEIProposta__c                 | picklist  | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Status Integração VEI PROPOSTA           | StatusIntegracaoVEIPROPOSTA__c         | picklist  | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Criado SF                                | CriadoSF__c                            | boolean   | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Situacao CAC Contato                     | SituacaoCACContato__c                  | picklist  | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Departamento                             | DWDepartamento__c                      | picklist  | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Tipo de contato                          | DWTipoContato__c                       | picklist  | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Ativo Passivo                            | DWAtivoPassivo__c                      | picklist  | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Origem CAC Contato                       | OrigemCACContato__c                    | picklist  | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Forma de contato                         | DWFormaContato__c                      | picklist  | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Somente peças                            | DWSomentePecas__c                      | boolean   | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Indicador presença                       | IndicadorPresenca__c                   | picklist  | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Consumidor Final                         | ConsumidorFinal__c                     | picklist  | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Caixa                                    | Caixa__c                               | picklist  | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Tipo de operação                         | TipoOperacao__c                        | picklist  | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Tipo OS                                  | TipoOs__c                              | picklist  | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Código exibição aprovação / proposta     | DWCodigoAprovacao__c                   | picklist  | Selecione qual código do produto deve ser utilizado nos e-mails de aprovação e proposta:
Código original: código nativo do Salesforce.
Código sistema: usa o código interno (Empresa + item).
Nenhum: nenhum código será exibido.                                                                                                                                                      |
| Previsão de entrega                      | DWPrevisaoEntrega__c                   | string    | -                                                                                                                                                                                                                                                                                                                                                                                      |
| ICMS ST                                  | DWICMSST__c                            | currency  | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Total geral                              | DWTotalGeral__c                        | currency  | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Após criação                             | DWAposCriacao__c                       | boolean   | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Código da loja                           | DWCodigoLoja__c                        | string    | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Contato                                  | DWContato__c                           | reference | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Despesas acessórias                      | DWDespesasAcessorias__c                | currency  | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Loja de faturamento                      | DWLoja__c                              | reference | Campo que indicará onde o carro será faturado (contabilizada a venda).                                                                                                                                                                                                                                                                                                                 |
| N°                                       | DWN__c                                 | string    | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Possui produtos em integração?           | DWPossuiProdutosIntegracao__c          | boolean   | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Valor do Veículo                         | DWValorVeiculo__c                      | currency  | O campo traz o valor do carro no estoque, mas permite editar para mais ou para menos conforme a negociação feita com o cliente. Esse campo quando editado, passará a ser o Preço do Veículo na minuta.                                                                                                                                                                                 |
| Total ICMS                               | DWTotalICMS__c                         | currency  | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Total                                    | DWTotal__c                             | currency  | Valor total da venda (oportunidade) com Itens + frete + despesas                                                                                                                                                                                                                                                                                                                       |
| Produto consultando impostos             | ProdutoConsultandoImpostos__c          | double    | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Origem Frente Caixa                      | DWOrigemFrenteCaixa__c                 | picklist  | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Tipo Servico OS ( Forma Pagamento )      | TipoServicoOS__c                       | picklist  | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Aprovador N1 de serviços                 | DWAprovadorN1Servicos__c               | reference | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Aprovador serviços                       | DWAprovadorN2Servicos__c               | reference | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Proximo Aprovador(Chatgpt)               | DWProximoAprovadorCHATGPT__c           | reference | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Status da aprovação de serviços          | DWStatusAprovacaoServicos__c           | picklist  | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Cliente faturamento - Peças              | DWClienteFaturamentoPecas__c           | reference | Cliente faturamento - Peças (480)                                                                                                                                                                                                                                                                                                                                                      |
| Qtd. de serviços de N1                   | DWQtdServicosN1__c                     | double    | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Qtd. de serviços (aprovação)             | DWQtdServicosN2__c                     | double    | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Acréscimo total (%)                      | DWAcrescimoTotalPerc__c                | percent   | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Acréscimo total                          | DWAcrescimoTotal__c                    | double    | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Desconto total (%)                       | DWDescontoTotalPerc__c                 | percent   | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Desconto total                           | DWDescontoTotal__c                     | currency  | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Saldo(%)                                 | DWSaldoPercForm__c                     | percent   | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Saldo($)                                 | DWSaldoVarForm__c                      | currency  | -                                                                                                                                                                                                                                                                                                                                                                                      |
| Cliente faturamento - Serviços           | DWClienteFaturamentoServicos__c        | reference | Cliente faturamento serviços (752)                                                                                                                                                                                                                                                                                                                                                     |
| Cliente p/ emissão NF - Peças            | DWClienteEmissaoNFPecas__c             | reference | Cliente para emissão da NF - Peças (665)                                                                                                                                                                                                                                                                                                                                               |
| Cliente p/ emissão NF - Serviços         | DWClienteEmissaoNFServicos__c          | reference | Cliente para emissão da NF                                                                                                                                                                                                                                                                                                                                                             |

## Relacionamentos Filhos

| Rótulo                                | Nome de relacionamento                | Campo de referência              | Objeto Relacionado                   |
| ------------------------------------- | ------------------------------------- | -------------------------------- | ------------------------------------ |
| AIInsightValue                        | -                                     | SobjectLookupValueId             | AIInsightValue                       |
| AIRecordInsight                       | -                                     | TargetId                         | AIRecordInsight                      |
| AccountPartners                       | AccountPartners                       | OpportunityId                    | AccountPartner                       |
| ReferenceRecords                      | ReferenceRecords                      | ReferenceRecordId                | AccountPlanObjMeasRela               |
| AccountPlanObjMeasRelaChangeEvent     | -                                     | ReferenceRecordId                | AccountPlanObjMeasRelaChangeEvent    |
| ActionPlans                           | ActionPlans                           | TargetId                         | ActionPlan                           |
| ActionPlanChangeEvent                 | -                                     | TargetId                         | ActionPlanChangeEvent                |
| ActivityHistories                     | ActivityHistories                     | WhatId                           | ActivityHistory                      |
| AgentWork                             | -                                     | WorkItemId                       | AgentWork                            |
| AgentWorkChangeEvent                  | -                                     | WorkItemId                       | AgentWorkChangeEvent                 |
| ApprovalSubmissions                   | ApprovalSubmissions                   | RelatedRecordId                  | ApprovalSubmission                   |
| ApprovalWorkItems                     | ApprovalWorkItems                     | RelatedRecordId                  | ApprovalWorkItem                     |
| Ativos__r                             | Ativos__r                             | Oportunidade__c                  | Asset                                |
| AttachedContentDocuments              | AttachedContentDocuments              | LinkedEntityId                   | AttachedContentDocument              |
| AttachedContentNotes                  | AttachedContentNotes                  | LinkedEntityId                   | AttachedContentNote                  |
| Attachments                           | Attachments                           | ParentId                         | Attachment                           |
| CampaignInfluences                    | CampaignInfluences                    | OpportunityId                    | CampaignInfluence                    |
| Casos__r                              | Casos__r                              | DWOportunidade__c                | Case                                 |
| RecordAssociatedGroups                | RecordAssociatedGroups                | RecordId                         | CollaborationGroupRecord             |
| CollaborationGroupRecordChangeEvent   | -                                     | RecordId                         | CollaborationGroupRecordChangeEvent  |
| CombinedAttachments                   | CombinedAttachments                   | ParentId                         | CombinedAttachment                   |
| CondicoesPagamento__r                 | CondicoesPagamento__r                 | Oportunidade__c                  | CondicaoPagamento__c                 |
| ContactRequests                       | ContactRequests                       | WhatId                           | ContactRequest                       |
| ContentDistribution                   | -                                     | RelatedRecordId                  | ContentDistribution                  |
| ContentDocumentLinks                  | ContentDocumentLinks                  | LinkedEntityId                   | ContentDocumentLink                  |
| ContentDocumentLinkChangeEvent        | -                                     | LinkedEntityId                   | ContentDocumentLinkChangeEvent       |
| ContentVersion                        | -                                     | FirstPublishLocationId           | ContentVersion                       |
| ContentVersionChangeEvent             | -                                     | FirstPublishLocationId           | ContentVersionChangeEvent            |
| Oportunidades_da_ordem_de_trabalho__r | Oportunidades_da_ordem_de_trabalho__r | Oportunidade__c                  | DWOportunidadeOrdemTrabalho__c       |
| DW_NPX__Http_Request_Logs__r          | DW_NPX__Http_Request_Logs__r          | DW_NPX__Oportunidade__c          | DW_NPX__HttpRequestLog__c            |
| DocumentosAnexados__r                 | DocumentosAnexados__r                 | Oportunidade__c                  | DocumentoAnexado__c                  |
| Emails                                | Emails                                | RelatedToId                      | EmailMessage                         |
| EmailMessageChangeEvent               | -                                     | RelatedToId                      | EmailMessageChangeEvent              |
| FeedSubscriptionsForEntity            | FeedSubscriptionsForEntity            | ParentId                         | EntitySubscription                   |
| Events                                | Events                                | WhatId                           | Event                                |
| EventChangeEvent                      | -                                     | WhatId                           | EventChangeEvent                     |
| EventRelations                        | EventRelations                        | RelationId                       | EventRelation                        |
| EventRelationChangeEvent              | -                                     | RelationId                       | EventRelationChangeEvent             |
| FeedComment                           | -                                     | ParentId                         | FeedComment                          |
| FeedItem                              | -                                     | ParentId                         | FeedItem                             |
| FieldChangeSnapshots                  | FieldChangeSnapshots                  | ParentId                         | FieldChangeSnapshot                  |
| FlowExecutionErrorEvent               | -                                     | ContextRecordId                  | FlowExecutionErrorEvent              |
| FlowOrchestrationWorkItems            | FlowOrchestrationWorkItems            | RelatedRecordId                  | FlowOrchestrationWorkItem            |
| FlowRecordRelation                    | -                                     | RelatedRecordId                  | FlowRecordRelation                   |
| ForecastingFact                       | -                                     | OpportunityId                    | ForecastingFact                      |
| ForecastingItem__hd                   | -                                     | ParentId                         | ForecastingItem__hd                  |
| ForecastingSrcRecJudgment             | -                                     | ReferenceObjectId                | ForecastingSrcRecJudgment            |
| Http_Request_Logs__r                  | Http_Request_Logs__r                  | Oportunidade__c                  | HttpRequestLog__c                    |
| Lead                                  | -                                     | ConvertedOpportunityId           | Lead                                 |
| LeadChangeEvent                       | -                                     | ConvertedOpportunityId           | LeadChangeEvent                      |
| ListEmails                            | ListEmails                            | RelatedToId                      | ListEmail                            |
| ListEmailChangeEvent                  | -                                     | RelatedToId                      | ListEmailChangeEvent                 |
| ParentEntities                        | ParentEntities                        | ParentEntityId                   | NetworkActivityAudit                 |
| NetworkFeedResponseMetric             | -                                     | ParentRecordId                   | NetworkFeedResponseMetric            |
| Notes                                 | Notes                                 | ParentId                         | Note                                 |
| NotesAndAttachments                   | NotesAndAttachments                   | ParentId                         | NoteAndAttachment                    |
| OpenActivities                        | OpenActivities                        | WhatId                           | OpenActivity                         |
| DW_SPT__Oportunidades__r              | DW_SPT__Oportunidades__r              | DW_SPT__OportunidadePrincipal__c | Opportunity                          |
| OpportunityCompetitors                | OpportunityCompetitors                | OpportunityId                    | OpportunityCompetitor                |
| OpportunityContactRoles               | OpportunityContactRoles               | OpportunityId                    | OpportunityContactRole               |
| OpportunityContactRoleChangeEvent     | -                                     | OpportunityId                    | OpportunityContactRoleChangeEvent    |
| Feeds                                 | Feeds                                 | ParentId                         | OpportunityFeed                      |
| Histories                             | Histories                             | OpportunityId                    | OpportunityFieldHistory              |
| OpportunityHistories                  | OpportunityHistories                  | OpportunityId                    | OpportunityHistory                   |
| OpportunityLineItems                  | OpportunityLineItems                  | OpportunityId                    | OpportunityLineItem                  |
| OpportunityLineItemChangeEvent        | -                                     | OpportunityId                    | OpportunityLineItemChangeEvent       |
| OpportunityPartnersFrom               | OpportunityPartnersFrom               | OpportunityId                    | OpportunityPartner                   |
| OpportunityRelatedDeleteLogs          | OpportunityRelatedDeleteLogs          | OpportunityId                    | OpportunityRelatedDeleteLog          |
| Shares                                | Shares                                | OpportunityId                    | OpportunityShare                     |
| OpportunitySplits                     | OpportunitySplits                     | OpportunityId                    | OpportunitySplit                     |
| OpportunitySplitChangeEvent           | -                                     | OpportunityId                    | OpportunitySplitChangeEvent          |
| OpportunityTeamMembers                | OpportunityTeamMembers                | OpportunityId                    | OpportunityTeamMember                |
| Opportunity__hd                       | -                                     | ParentId                         | Opportunity__hd                      |
| Orders                                | Orders                                | OpportunityId                    | Order                                |
| OrderChangeEvent                      | -                                     | OpportunityId                    | OrderChangeEvent                     |
| OutgoingEmail                         | -                                     | RelatedToId                      | OutgoingEmail                        |
| Partners                              | Partners                              | OpportunityId                    | Partner                              |
| PendingServiceRouting                 | -                                     | WorkItemId                       | PendingServiceRouting                |
| PendingServiceRoutingChangeEvent      | -                                     | WorkItemId                       | PendingServiceRoutingChangeEvent     |
| PendingServiceRoutingInteractionInfo  | -                                     | PrimaryRecordId                  | PendingServiceRoutingInteractionInfo |
| PendingServiceRoutingInteractionInfo  | -                                     | TargetObjectId                   | PendingServiceRoutingInteractionInfo |
| ProcessInstances                      | ProcessInstances                      | TargetObjectId                   | ProcessInstance                      |
| ProcessInstanceChangeEvent            | -                                     | TargetObjectId                   | ProcessInstanceChangeEvent           |
| ProcessSteps                          | ProcessSteps                          | TargetObjectId                   | ProcessInstanceHistory               |
| Quotes                                | Quotes                                | OpportunityId                    | Quote                                |
| QuoteChangeEvent                      | -                                     | OpportunityId                    | QuoteChangeEvent                     |
| RecentFieldChanges                    | RecentFieldChanges                    | ParentId                         | RecentFieldChange                    |
| RecordActions                         | RecordActions                         | RecordId                         | RecordAction                         |
| RecordActionHistories                 | RecordActionHistories                 | ParentRecordId                   | RecordActionHistory                  |
| ServiceAppointments                   | ServiceAppointments                   | ParentRecordId                   | ServiceAppointment                   |
| ServiceAppointmentChangeEvent         | -                                     | ParentRecordId                   | ServiceAppointmentChangeEvent        |
| SurveySubjectEntities                 | SurveySubjectEntities                 | SubjectId                        | SurveySubject                        |
| SurveySubjectChangeEvent              | -                                     | SubjectId                        | SurveySubjectChangeEvent             |
| Swarms                                | Swarms                                | RelatedRecordId                  | Swarm                                |
| SwarmMembers                          | SwarmMembers                          | RelatedRecordId                  | SwarmMember                          |
| Tasks                                 | Tasks                                 | WhatId                           | Task                                 |
| TaskChangeEvent                       | -                                     | WhatId                           | TaskChangeEvent                      |
| TaskRelations                         | TaskRelations                         | RelationId                       | TaskRelation                         |
| TaskRelationChangeEvent               | -                                     | RelationId                       | TaskRelationChangeEvent              |
| TopicAssignments                      | TopicAssignments                      | EntityId                         | TopicAssignment                      |
| UserDefinedLabelAssignments           | UserDefinedLabelAssignments           | ItemId                           | UserDefinedLabelAssignment           |
| UserPrioritizedRecord                 | -                                     | TargetId                         | UserPrioritizedRecord                |
| VideoRelatedRecords                   | VideoRelatedRecords                   | RelatedRecordId                  | VideoCall                            |
| VideoCallChangeEvent                  | -                                     | RelatedRecordId                  | VideoCallChangeEvent                 |
| RelatedRecords                        | RelatedRecords                        | RelatedRecordId                  | VoiceCall                            |
| VoiceCallChangeEvent                  | -                                     | RelatedRecordId                  | VoiceCallChangeEvent                 |
| Ordens_de_trabalho__r                 | Ordens_de_trabalho__r                 | Oportunidade__c                  | WorkOrder                            |

## Tipos de Registro

| Nome       | Rótulo   |
| ---------- | -------- |
| DWMaquinas | Máquinas |
| DWOficina  | Oficina  |
| DWPecas    | Peças    |

## Visualizações de Lista

### Máquinas

Consulta: SELECT Name, Account.Name, convertCurrency(Amount), CloseDate, DWCondicaoPagamento__r.Name, toLabel(StageName), Probability, toLabel(Type), toLabel(LeadSource), Owner.Name, CreatedDate, RecordType.Name, Id, RecordTypeId, CurrencyIsoCode, LastModifiedDate, SystemModstamp, Account.Id, AccountId, Account.RecordTypeId, DWCondicaoPagamento__c, Owner.Id, OwnerId FROM Opportunity WHERE RecordTypeId = '012U60000077fVR' ORDER BY CreatedDate DESC NULLS LAST, Id DESC NULLS LAST

| Rótulo                           | Campo                       |
| -------------------------------- | --------------------------- |
| Nome da oportunidade             | Name                        |
| Nome da conta                    | Account.Name                |
| Valor                            | Amount                      |
| Data de fechamento               | CloseDate                   |
| Condição de pagamento            | DWCondicaoPagamento__r.Name |
| Fase                             | StageName                   |
| Probabilidade (%)                | Probability                 |
| Tipo                             | Type                        |
| Origem do lead                   | LeadSource                  |
| Nome completo do proprietário    | Owner.Name                  |
| Data de criação                  | CreatedDate                 |
| Tipo de registro de oportunidade | RecordType.Name             |
| ID da oportunidade               | Id                          |
| ID do tipo de registro           | RecordTypeId                |
| Moeda da oportunidade            | CurrencyIsoCode             |
| Data da última modificação       | LastModifiedDate            |
| Modstamp do sistema              | SystemModstamp              |
| ID da conta                      | Account.Id                  |
| ID da conta                      | AccountId                   |
| ID do tipo de registro           | Account.RecordTypeId        |
| Condição de pagamento            | DWCondicaoPagamento__c      |
| ID do usuário                    | Owner.Id                    |
| ID do proprietário               | OwnerId                     |

### Peças

Consulta: SELECT Name, Account.Name, toLabel(StageName), CreatedDate, CloseDate, convertCurrency(Amount), Owner.Alias, Id, RecordTypeId, CurrencyIsoCode, LastModifiedDate, SystemModstamp, Account.Id, AccountId, Account.RecordTypeId, Owner.Id, OwnerId FROM Opportunity WHERE RecordTypeId = '012HZ000004tvct' ORDER BY Amount DESC NULLS LAST, Id DESC NULLS LAST

| Rótulo                                | Campo                |
| ------------------------------------- | -------------------- |
| Nome da oportunidade                  | Name                 |
| Nome da conta                         | Account.Name         |
| Fase                                  | StageName            |
| Data de criação                       | CreatedDate          |
| Data de fechamento                    | CloseDate            |
| Valor                                 | Amount               |
| Alias do proprietário da oportunidade | Owner.Alias          |
| ID da oportunidade                    | Id                   |
| ID do tipo de registro                | RecordTypeId         |
| Moeda da oportunidade                 | CurrencyIsoCode      |
| Data da última modificação            | LastModifiedDate     |
| Modstamp do sistema                   | SystemModstamp       |
| ID da conta                           | Account.Id           |
| ID da conta                           | AccountId            |
| ID do tipo de registro                | Account.RecordTypeId |
| ID do usuário                         | Owner.Id             |
| ID do proprietário                    | OwnerId              |

### Perdidas

Consulta: SELECT Name, Account.Name, convertCurrency(Amount), CloseDate, DWCondicaoPagamento__r.Name, toLabel(StageName), Probability, toLabel(Type), toLabel(LeadSource), Owner.Name, CreatedDate, RecordType.Name, LastModifiedDate, Id, RecordTypeId, CurrencyIsoCode, SystemModstamp, Account.Id, AccountId, Account.RecordTypeId, DWCondicaoPagamento__c, Owner.Id, OwnerId FROM Opportunity WHERE StageName = 'Perdido' ORDER BY CreatedDate DESC NULLS LAST, Id DESC NULLS LAST

| Rótulo                           | Campo                       |
| -------------------------------- | --------------------------- |
| Nome da oportunidade             | Name                        |
| Nome da conta                    | Account.Name                |
| Valor                            | Amount                      |
| Data de fechamento               | CloseDate                   |
| Condição de pagamento            | DWCondicaoPagamento__r.Name |
| Fase                             | StageName                   |
| Probabilidade (%)                | Probability                 |
| Tipo                             | Type                        |
| Origem do lead                   | LeadSource                  |
| Nome completo do proprietário    | Owner.Name                  |
| Data de criação                  | CreatedDate                 |
| Tipo de registro de oportunidade | RecordType.Name             |
| Data da última modificação       | LastModifiedDate            |
| ID da oportunidade               | Id                          |
| ID do tipo de registro           | RecordTypeId                |
| Moeda da oportunidade            | CurrencyIsoCode             |
| Modstamp do sistema              | SystemModstamp              |
| ID da conta                      | Account.Id                  |
| ID da conta                      | AccountId                   |
| ID do tipo de registro           | Account.RecordTypeId        |
| Condição de pagamento            | DWCondicaoPagamento__c      |
| ID do usuário                    | Owner.Id                    |
| ID do proprietário               | OwnerId                     |

### Oportunidades Peças

Consulta: SELECT Name, Account.Name, convertCurrency(Amount), CloseDate, DWCondicaoPagamento__r.Name, toLabel(StageName), Probability, toLabel(Type), toLabel(LeadSource), Owner.Name, CreatedDate, RecordType.Name, LastModifiedDate, Id, RecordTypeId, CurrencyIsoCode, SystemModstamp, Account.Id, AccountId, Account.RecordTypeId, DWCondicaoPagamento__c, Owner.Id, OwnerId FROM Opportunity WHERE RecordTypeId = '012HZ000004tvct' ORDER BY CloseDate DESC NULLS LAST, Id DESC NULLS LAST

| Rótulo                           | Campo                       |
| -------------------------------- | --------------------------- |
| Nome da oportunidade             | Name                        |
| Nome da conta                    | Account.Name                |
| Valor                            | Amount                      |
| Data de fechamento               | CloseDate                   |
| Condição de pagamento            | DWCondicaoPagamento__r.Name |
| Fase                             | StageName                   |
| Probabilidade (%)                | Probability                 |
| Tipo                             | Type                        |
| Origem do lead                   | LeadSource                  |
| Nome completo do proprietário    | Owner.Name                  |
| Data de criação                  | CreatedDate                 |
| Tipo de registro de oportunidade | RecordType.Name             |
| Data da última modificação       | LastModifiedDate            |
| ID da oportunidade               | Id                          |
| ID do tipo de registro           | RecordTypeId                |
| Moeda da oportunidade            | CurrencyIsoCode             |
| Modstamp do sistema              | SystemModstamp              |
| ID da conta                      | Account.Id                  |
| ID da conta                      | AccountId                   |
| ID do tipo de registro           | Account.RecordTypeId        |
| Condição de pagamento            | DWCondicaoPagamento__c      |
| ID do usuário                    | Owner.Id                    |
| ID do proprietário               | OwnerId                     |

### Minhas oportunidades

Consulta: SELECT Name, Account.Name, convertCurrency(Amount), toLabel(StageName), CloseDate, Id, RecordTypeId, CurrencyIsoCode, CreatedDate, LastModifiedDate, SystemModstamp, Account.Id, AccountId, Account.RecordTypeId FROM Opportunity USING SCOPE mine WHERE RecordTypeId = '012as000000EPTX' ORDER BY Name ASC NULLS FIRST, Id ASC NULLS FIRST

| Rótulo                     | Campo                |
| -------------------------- | -------------------- |
| Nome da oportunidade       | Name                 |
| Nome da conta              | Account.Name         |
| Valor                      | Amount               |
| Fase                       | StageName            |
| Data de fechamento         | CloseDate            |
| ID da oportunidade         | Id                   |
| ID do tipo de registro     | RecordTypeId         |
| Moeda da oportunidade      | CurrencyIsoCode      |
| Data de criação            | CreatedDate          |
| Data da última modificação | LastModifiedDate     |
| Modstamp do sistema        | SystemModstamp       |
| ID da conta                | Account.Id           |
| ID da conta                | AccountId            |
| ID do tipo de registro     | Account.RecordTypeId |

### Todas as oportunidades

Consulta: SELECT Name, Account.Name, convertCurrency(Amount), CloseDate, DWCondicaoPagamento__r.Name, toLabel(StageName), Probability, toLabel(Type), toLabel(LeadSource), Owner.Name, CreatedDate, RecordType.Name, LastModifiedDate, Id, RecordTypeId, CurrencyIsoCode, SystemModstamp, Account.Id, AccountId, Account.RecordTypeId, DWCondicaoPagamento__c, Owner.Id, OwnerId FROM Opportunity ORDER BY CreatedDate DESC NULLS LAST, Id DESC NULLS LAST

| Rótulo                           | Campo                       |
| -------------------------------- | --------------------------- |
| Nome da oportunidade             | Name                        |
| Nome da conta                    | Account.Name                |
| Valor                            | Amount                      |
| Data de fechamento               | CloseDate                   |
| Condição de pagamento            | DWCondicaoPagamento__r.Name |
| Fase                             | StageName                   |
| Probabilidade (%)                | Probability                 |
| Tipo                             | Type                        |
| Origem do lead                   | LeadSource                  |
| Nome completo do proprietário    | Owner.Name                  |
| Data de criação                  | CreatedDate                 |
| Tipo de registro de oportunidade | RecordType.Name             |
| Data da última modificação       | LastModifiedDate            |
| ID da oportunidade               | Id                          |
| ID do tipo de registro           | RecordTypeId                |
| Moeda da oportunidade            | CurrencyIsoCode             |
| Modstamp do sistema              | SystemModstamp              |
| ID da conta                      | Account.Id                  |
| ID da conta                      | AccountId                   |
| ID do tipo de registro           | Account.RecordTypeId        |
| Condição de pagamento            | DWCondicaoPagamento__c      |
| ID do usuário                    | Owner.Id                    |
| ID do proprietário               | OwnerId                     |

### Pipeline de oportunidades

Consulta: SELECT Name, Account.Name, convertCurrency(Amount), CloseDate, toLabel(StageName), Owner.Alias, Id, RecordTypeId, CurrencyIsoCode, CreatedDate, LastModifiedDate, SystemModstamp, Account.Id, AccountId, Account.RecordTypeId, Owner.Id, OwnerId FROM Opportunity USING SCOPE mine WHERE IsClosed = false OR CloseDate >= LAST_N_DAYS:30 ORDER BY Name ASC NULLS FIRST, Id ASC NULLS FIRST

| Rótulo                                | Campo                |
| ------------------------------------- | -------------------- |
| Nome da oportunidade                  | Name                 |
| Nome da conta                         | Account.Name         |
| Valor                                 | Amount               |
| Data de fechamento                    | CloseDate            |
| Fase                                  | StageName            |
| Alias do proprietário da oportunidade | Owner.Alias          |
| ID da oportunidade                    | Id                   |
| ID do tipo de registro                | RecordTypeId         |
| Moeda da oportunidade                 | CurrencyIsoCode      |
| Data de criação                       | CreatedDate          |
| Data da última modificação            | LastModifiedDate     |
| Modstamp do sistema                   | SystemModstamp       |
| ID da conta                           | Account.Id           |
| ID da conta                           | AccountId            |
| ID do tipo de registro                | Account.RecordTypeId |
| ID do usuário                         | Owner.Id             |
| ID do proprietário                    | OwnerId              |

### Fechando neste mês

Consulta: SELECT Name, Account.Name, convertCurrency(Amount), CloseDate, toLabel(StageName), Owner.Alias, Id, RecordTypeId, CurrencyIsoCode, CreatedDate, LastModifiedDate, SystemModstamp, Account.Id, AccountId, Account.RecordTypeId, Owner.Id, OwnerId FROM Opportunity WHERE IsClosed = false AND CloseDate = THIS_MONTH ORDER BY Name ASC NULLS FIRST, Id ASC NULLS FIRST

| Rótulo                                | Campo                |
| ------------------------------------- | -------------------- |
| Nome da oportunidade                  | Name                 |
| Nome da conta                         | Account.Name         |
| Valor                                 | Amount               |
| Data de fechamento                    | CloseDate            |
| Fase                                  | StageName            |
| Alias do proprietário da oportunidade | Owner.Alias          |
| ID da oportunidade                    | Id                   |
| ID do tipo de registro                | RecordTypeId         |
| Moeda da oportunidade                 | CurrencyIsoCode      |
| Data de criação                       | CreatedDate          |
| Data da última modificação            | LastModifiedDate     |
| Modstamp do sistema                   | SystemModstamp       |
| ID da conta                           | Account.Id           |
| ID da conta                           | AccountId            |
| ID do tipo de registro                | Account.RecordTypeId |
| ID do usuário                         | Owner.Id             |
| ID do proprietário                    | OwnerId              |

### Ganhos

Consulta: SELECT Name, Account.Name, convertCurrency(Amount), CloseDate, toLabel(StageName), CreatedDate, Owner.Alias, Id, RecordTypeId, CurrencyIsoCode, LastModifiedDate, SystemModstamp, Account.Id, AccountId, Account.RecordTypeId, Owner.Id, OwnerId FROM Opportunity WHERE IsWon = true AND IsClosed = true ORDER BY CreatedDate DESC NULLS LAST, Id DESC NULLS LAST

| Rótulo                                | Campo                |
| ------------------------------------- | -------------------- |
| Nome da oportunidade                  | Name                 |
| Nome da conta                         | Account.Name         |
| Valor                                 | Amount               |
| Data de fechamento                    | CloseDate            |
| Fase                                  | StageName            |
| Data de criação                       | CreatedDate          |
| Alias do proprietário da oportunidade | Owner.Alias          |
| ID da oportunidade                    | Id                   |
| ID do tipo de registro                | RecordTypeId         |
| Moeda da oportunidade                 | CurrencyIsoCode      |
| Data da última modificação            | LastModifiedDate     |
| Modstamp do sistema                   | SystemModstamp       |
| ID da conta                           | Account.Id           |
| ID da conta                           | AccountId            |
| ID do tipo de registro                | Account.RecordTypeId |
| ID do usuário                         | Owner.Id             |
| ID do proprietário                    | OwnerId              |

### Novidades nesta semana

Consulta: SELECT Name, Account.Name, convertCurrency(Amount), CloseDate, toLabel(StageName), Owner.Alias, Id, RecordTypeId, CurrencyIsoCode, CreatedDate, LastModifiedDate, SystemModstamp, Account.Id, AccountId, Account.RecordTypeId, Owner.Id, OwnerId FROM Opportunity WHERE CreatedDate = THIS_WEEK ORDER BY Name ASC NULLS FIRST, Id ASC NULLS FIRST

| Rótulo                                | Campo                |
| ------------------------------------- | -------------------- |
| Nome da oportunidade                  | Name                 |
| Nome da conta                         | Account.Name         |
| Valor                                 | Amount               |
| Data de fechamento                    | CloseDate            |
| Fase                                  | StageName            |
| Alias do proprietário da oportunidade | Owner.Alias          |
| ID da oportunidade                    | Id                   |
| ID do tipo de registro                | RecordTypeId         |
| Moeda da oportunidade                 | CurrencyIsoCode      |
| Data de criação                       | CreatedDate          |
| Data da última modificação            | LastModifiedDate     |
| Modstamp do sistema                   | SystemModstamp       |
| ID da conta                           | Account.Id           |
| ID da conta                           | AccountId            |
| ID do tipo de registro                | Account.RecordTypeId |
| ID do usuário                         | Owner.Id             |
| ID do proprietário                    | OwnerId              |

### Fechando no próximo mês

Consulta: SELECT Name, Account.Name, convertCurrency(Amount), CloseDate, toLabel(StageName), Owner.Alias, Id, RecordTypeId, CurrencyIsoCode, CreatedDate, LastModifiedDate, SystemModstamp, Account.Id, AccountId, Account.RecordTypeId, Owner.Id, OwnerId FROM Opportunity WHERE IsClosed = false AND CloseDate = NEXT_MONTH ORDER BY Name ASC NULLS FIRST, Id ASC NULLS FIRST

| Rótulo                                | Campo                |
| ------------------------------------- | -------------------- |
| Nome da oportunidade                  | Name                 |
| Nome da conta                         | Account.Name         |
| Valor                                 | Amount               |
| Data de fechamento                    | CloseDate            |
| Fase                                  | StageName            |
| Alias do proprietário da oportunidade | Owner.Alias          |
| ID da oportunidade                    | Id                   |
| ID do tipo de registro                | RecordTypeId         |
| Moeda da oportunidade                 | CurrencyIsoCode      |
| Data de criação                       | CreatedDate          |
| Data da última modificação            | LastModifiedDate     |
| Modstamp do sistema                   | SystemModstamp       |
| ID da conta                           | Account.Id           |
| ID da conta                           | AccountId            |
| ID do tipo de registro                | Account.RecordTypeId |
| ID do usuário                         | Owner.Id             |
| ID do proprietário                    | OwnerId              |

### Oportunidades exibidas recentemente

Consulta: SELECT Name, Account.Name, convertCurrency(Amount), CloseDate, toLabel(StageName), Owner.Alias, Id, RecordTypeId, CurrencyIsoCode, CreatedDate, LastModifiedDate, SystemModstamp, Account.Id, AccountId, Account.RecordTypeId, Owner.Id, OwnerId FROM Opportunity USING SCOPE mru ORDER BY Name ASC NULLS FIRST, Id ASC NULLS FIRST

| Rótulo                                | Campo                |
| ------------------------------------- | -------------------- |
| Nome da oportunidade                  | Name                 |
| Nome da conta                         | Account.Name         |
| Valor                                 | Amount               |
| Data de fechamento                    | CloseDate            |
| Fase                                  | StageName            |
| Alias do proprietário da oportunidade | Owner.Alias          |
| ID da oportunidade                    | Id                   |
| ID do tipo de registro                | RecordTypeId         |
| Moeda da oportunidade                 | CurrencyIsoCode      |
| Data de criação                       | CreatedDate          |
| Data da última modificação            | LastModifiedDate     |
| Modstamp do sistema                   | SystemModstamp       |
| ID da conta                           | Account.Id           |
| ID da conta                           | AccountId            |
| ID do tipo de registro                | Account.RecordTypeId |
| ID do usuário                         | Owner.Id             |
| ID do proprietário                    | OwnerId              |

### Kanban

Consulta: SELECT Name, Account.Name, toLabel(StageName), CloseDate, convertCurrency(Amount), Owner.Alias, Id, RecordTypeId, CurrencyIsoCode, CreatedDate, LastModifiedDate, SystemModstamp, Account.Id, AccountId, Account.RecordTypeId, Owner.Id, OwnerId FROM Opportunity USING SCOPE mine ORDER BY Name ASC NULLS FIRST, Id ASC NULLS FIRST

| Rótulo                                | Campo                |
| ------------------------------------- | -------------------- |
| Nome da oportunidade                  | Name                 |
| Nome da conta                         | Account.Name         |
| Fase                                  | StageName            |
| Data de fechamento                    | CloseDate            |
| Valor                                 | Amount               |
| Alias do proprietário da oportunidade | Owner.Alias          |
| ID da oportunidade                    | Id                   |
| ID do tipo de registro                | RecordTypeId         |
| Moeda da oportunidade                 | CurrencyIsoCode      |
| Data de criação                       | CreatedDate          |
| Data da última modificação            | LastModifiedDate     |
| Modstamp do sistema                   | SystemModstamp       |
| ID da conta                           | Account.Id           |
| ID da conta                           | AccountId            |
| ID do tipo de registro                | Account.RecordTypeId |
| ID do usuário                         | Owner.Id             |
| ID do proprietário                    | OwnerId              |

### Oportunidades criadas hoje

Consulta: SELECT Name, Account.Name, convertCurrency(Amount), CloseDate, DWCondicaoPagamento__r.Name, DWPrazoMedioCondicaoPagamento__c, toLabel(StageName), CreatedDate, Id, RecordTypeId, CurrencyIsoCode, LastModifiedDate, SystemModstamp, Account.Id, AccountId, Account.RecordTypeId, DWCondicaoPagamento__c FROM Opportunity WHERE CreatedDate = TODAY ORDER BY Name ASC NULLS FIRST, Id ASC NULLS FIRST

| Rótulo                               | Campo                            |
| ------------------------------------ | -------------------------------- |
| Nome da oportunidade                 | Name                             |
| Nome da conta                        | Account.Name                     |
| Valor                                | Amount                           |
| Data de fechamento                   | CloseDate                        |
| Condição de pagamento                | DWCondicaoPagamento__r.Name      |
| Prazo médio da condição de pagamento | DWPrazoMedioCondicaoPagamento__c |
| Fase                                 | StageName                        |
| Data de criação                      | CreatedDate                      |
| ID da oportunidade                   | Id                               |
| ID do tipo de registro               | RecordTypeId                     |
| Moeda da oportunidade                | CurrencyIsoCode                  |
| Data da última modificação           | LastModifiedDate                 |
| Modstamp do sistema                  | SystemModstamp                   |
| ID da conta                          | Account.Id                       |
| ID da conta                          | AccountId                        |
| ID do tipo de registro               | Account.RecordTypeId             |
| Condição de pagamento                | DWCondicaoPagamento__c           |

### Testes Odenir

Consulta: SELECT Name, Account.Name, convertCurrency(Amount), CloseDate, DWCondicaoPagamento__r.Name, toLabel(StageName), Probability, toLabel(Type), toLabel(LeadSource), Owner.Name, CreatedDate, Id, RecordTypeId, CurrencyIsoCode, LastModifiedDate, SystemModstamp, Account.Id, AccountId, Account.RecordTypeId, DWCondicaoPagamento__c, Owner.Id, OwnerId FROM Opportunity WHERE DWTipoTransacao__c != null ORDER BY Name ASC NULLS FIRST, Id ASC NULLS FIRST

| Rótulo                        | Campo                       |
| ----------------------------- | --------------------------- |
| Nome da oportunidade          | Name                        |
| Nome da conta                 | Account.Name                |
| Valor                         | Amount                      |
| Data de fechamento            | CloseDate                   |
| Condição de pagamento         | DWCondicaoPagamento__r.Name |
| Fase                          | StageName                   |
| Probabilidade (%)             | Probability                 |
| Tipo                          | Type                        |
| Origem do lead                | LeadSource                  |
| Nome completo do proprietário | Owner.Name                  |
| Data de criação               | CreatedDate                 |
| ID da oportunidade            | Id                          |
| ID do tipo de registro        | RecordTypeId                |
| Moeda da oportunidade         | CurrencyIsoCode             |
| Data da última modificação    | LastModifiedDate            |
| Modstamp do sistema           | SystemModstamp              |
| ID da conta                   | Account.Id                  |
| ID da conta                   | AccountId                   |
| ID do tipo de registro        | Account.RecordTypeId        |
| Condição de pagamento         | DWCondicaoPagamento__c      |
| ID do usuário                 | Owner.Id                    |
| ID do proprietário            | OwnerId                     |

## Acionadores de Fluxo

### DW - Ativo - After (upsert) - Inserção de plano de ação

Insere um plano de ação no Ativo assim que for preenchido o campo "Data de início da garantia". (Criado por Anderson, 08/08/2025)

| Tipo de acionador | Tipo de registro |
| ----------------- | ---------------- |
| RecordAfterSave   | Update           |

### DW - Before Flow - Oportunidade (Validar Preço Zerado)

DW - Before Flow - Oportunidade (Validar Preço Zerado) {!$Flow.CurrentDateTime}

| Tipo de acionador | Tipo de registro |
| ----------------- | ---------------- |
| RecordAfterSave   | Update           |

### DW - Busca custos de frete da cotação de frete para opp (faturamento)

DW - Busca custos de frete da cotação de frete para opp (faturamento) {!$Flow.CurrentDateTime}

| Tipo de acionador | Tipo de registro |
| ----------------- | ---------------- |
| RecordAfterSave   | CreateAndUpdate  |

### DW - Busca custos de frete da cotação de frete para opp (produção)

DW - Busca custos de frete da cotação de frete para opp {!$Flow.CurrentDateTime}

| Tipo de acionador | Tipo de registro |
| ----------------- | ---------------- |
| RecordAfterSave   | CreateAndUpdate  |

### DW - Calcula valor do frete

DW - Calcula valor do frete {!$Flow.CurrentDateTime}

| Tipo de acionador | Tipo de registro |
| ----------------- | ---------------- |
| RecordBeforeSave  | CreateAndUpdate  |

### DW - Fator de precificação de frete

DW - Fator de precificação de frete {!$Flow.CurrentDateTime}

| Tipo de acionador | Tipo de registro |
| ----------------- | ---------------- |
| RecordAfterSave   | Update           |

### DW - Oportunidade - Before Flow - Avaliar aprovação financeira

Esse fluxo avalie e reavalia a necessidade das aprovação financeira.

| Tipo de acionador | Tipo de registro |
| ----------------- | ---------------- |
| RecordBeforeSave  | CreateAndUpdate  |

### DW - Oportunidade - Before Flow - Avaliar aprovação logística

Esse fluxo avalie e reavalia a necessidade das aprovação logística.

| Tipo de acionador | Tipo de registro |
| ----------------- | ---------------- |
| RecordBeforeSave  | CreateAndUpdate  |

### DW - Oportunidade - Before Flow - Avaliar aprovação comercial

Esse fluxo avalie e reavalia a necessidade das aprovações comercial.

| Tipo de acionador | Tipo de registro |
| ----------------- | ---------------- |
| RecordBeforeSave  | CreateAndUpdate  |

### DW - Opportunity - Validação Condições Pagamento – Avanço de Fase

DW - OPORTUNIT {!$Flow.CurrentDateTime}

| Tipo de acionador | Tipo de registro |
| ----------------- | ---------------- |
| RecordBeforeSave  | CreateAndUpdate  |

### DW - Propaga data solicitada de entrega para produtos

DW - Propaga data solicitada de entrega para produtos {!$Flow.CurrentDateTime}

| Tipo de acionador | Tipo de registro |
| ----------------- | ---------------- |
| RecordAfterSave   | CreateAndUpdate  |

### DW - Propaga período solicitado para entrega para produtos

DW - Propaga período solicitado para entrega para produtos {!$Flow.CurrentDateTime}

| Tipo de acionador | Tipo de registro |
| ----------------- | ---------------- |
| RecordAfterSave   | CreateAndUpdate  |

### DW - Busca cotação de frete filial de faturamento -> destino

DW - Busca cotação de frete filial de faturamento -> destino {!$Flow.CurrentDateTime}

| Tipo de acionador | Tipo de registro |
| ----------------- | ---------------- |
| RecordBeforeSave  | CreateAndUpdate  |

### DW - Busca cotação de frete filial de produção -> destino

DW - Busca cotação de frete filial de produção -> destino {!$Flow.CurrentDateTime}

| Tipo de acionador | Tipo de registro |
| ----------------- | ---------------- |
| RecordBeforeSave  | CreateAndUpdate  |

### DW - Define aprovadores comercial conforme hieraquia

DW - Define aprovadores comercial conforme hieraquia {!$Flow.CurrentDateTime}

| Tipo de acionador | Tipo de registro |
| ----------------- | ---------------- |
| RecordBeforeSave  | CreateAndUpdate  |

### DW - Define aprovadores financeiros conforme hieraquia

DW - Define aprovadores comercial conforme hieraquia {!$Flow.CurrentDateTime}

| Tipo de acionador | Tipo de registro |
| ----------------- | ---------------- |
| RecordBeforeSave  | CreateAndUpdate  |

### DW NPX | Acionar cálculo horizontal de resumo

Fluxo automático sem ações, decisões ou atualizações; não possui pontos de entrada ou etapas definidas.  
Resultado principal: nenhum processamento ocorre, o fluxo está vazio ou em branco.

| Tipo de acionador | Tipo de registro |
| ----------------- | ---------------- |
| RecordAfterSave   | Update           |

### DW NPX | Acionar cálculo horizontal de resumo

Fluxo automático sem ações, decisões ou atualizações; não possui pontos de entrada ou etapas definidas. Objetivo e resultado principal não especificados, pois o fluxo está vazio e não executa nenhuma operação.

| Tipo de acionador | Tipo de registro |
| ----------------- | ---------------- |
| RecordAfterSave   | Update           |

### DW - Oportunidade - Ao fechar/ganha, gera uma OT de entrega técnica e envia para aprovação

DW - Oportunidade - Ao fechar/ganha, gera uma OT de entrega técnica e envia para aprovação {!$Flow.CurrentDateTime}

| Tipo de acionador | Tipo de registro |
| ----------------- | ---------------- |
| RecordAfterSave   | Update           |

### DW - Oportunidade - Aprovação de serviços da oportunidade

DW - Oportunidade - Aprovação de serviços da oportunidade {!$Flow.CurrentDateTime}

| Tipo de acionador | Tipo de registro |
| ----------------- | ---------------- |
| RecordAfterSave   | Update           |

### DW - Oportunidade - Atualizar status de OT para agendamento

DW - Oportunidade - Atualizar status de OT para peças {!$Flow.CurrentDateTime}

| Tipo de acionador | Tipo de registro |
| ----------------- | ---------------- |
| RecordAfterSave   | Update           |

### DW - Oportunidade - Atualizar status de OT para aprovação

DW - Oportunidade - Atualizar status de OT para aprovação {!$Flow.CurrentDateTime}

| Tipo de acionador | Tipo de registro |
| ----------------- | ---------------- |
| RecordAfterSave   | Update           |

### DW - Oportunidade - Atualizar status de OT para orçamento

DW - Oportunidade - Atualizar status de OT para orçamento {!$Flow.CurrentDateTime}

| Tipo de acionador | Tipo de registro |
| ----------------- | ---------------- |
| RecordAfterSave   | Update           |

### DW - Oportunidade - Atualizar status de OT para peças

DW - Oportunidade - Atualizar status de OT para peças {!$Flow.CurrentDateTime}

| Tipo de acionador | Tipo de registro |
| ----------------- | ---------------- |
| RecordAfterSave   | Update           |

### DW - Oportunidade - Avançar fase ao reservar todos os produtos

DW - Oportunidade - Avançar fase ao reservar todos os produtos {!$Flow.CurrentDateTime}

| Tipo de acionador | Tipo de registro |
| ----------------- | ---------------- |
| RecordAfterSave   | Update           |

### DW - Oportunidade - Avançar fase se aprovação desnecessária

DW - Oportunidade - Avançar fase se aprovação desnecessária {!$Flow.CurrentDateTime}

| Tipo de acionador | Tipo de registro |
| ----------------- | ---------------- |
| RecordAfterSave   | Update           |

### DW - Oportunidade - Avançar para fase de elaboração

DW - Oportunidade - Avançar para fase de elaboração {!$Flow.CurrentDateTime}

| Tipo de acionador | Tipo de registro |
| ----------------- | ---------------- |
| RecordBeforeSave  | Update           |

### DW - Oportunidade - Consultar impostos

DW - Oportunidade - Consultar impostos {!$Flow.CurrentDateTime}

| Tipo de acionador | Tipo de registro |
| ----------------- | ---------------- |
| RecordAfterSave   | CreateAndUpdate  |

### DW - Oportunidade - Criar peças (oli) de ordem de trabalho

DW - Oportunidade - Criar peças (oli) de ordem de trabalho {!$Flow.CurrentDateTime}

| Tipo de acionador | Tipo de registro |
| ----------------- | ---------------- |
| RecordAfterSave   | Create           |

### DW - Oportunidade - Criar produtos pelo plano de trabalho

DW - Oportunidade - Criar produtos pelo plano de trabalho {!$Flow.CurrentDateTime}

| Tipo de acionador | Tipo de registro |
| ----------------- | ---------------- |
| RecordAfterSave   | Create           |

### DW - Oportunidade - Definir origem frente caixa

DW - Oportunidade - Definir origem frente caixa {!$Flow.CurrentDateTime}

| Tipo de acionador | Tipo de registro |
| ----------------- | ---------------- |
| RecordAfterSave   | Update           |

### DW - Oportunidade - Definir se precisa de aprovação de serviços

DW - Oportunidade - Definir se precisa de aprovação de serviços {!$Flow.CurrentDateTime}

| Tipo de acionador | Tipo de registro |
| ----------------- | ---------------- |
| RecordAfterSave   | Update           |

### DW - Oportunidade - Definir tipo de OS

DW - Oportunidade - Definir tipo de OS {!$Flow.CurrentDateTime}

| Tipo de acionador | Tipo de registro |
| ----------------- | ---------------- |
| RecordAfterSave   | CreateAndUpdate  |

### DW - Oportunidade - Definir tipo de transação

DW - Oportunidade - Definir tipo de transação {!$Flow.CurrentDateTime}

| Tipo de acionador | Tipo de registro |
| ----------------- | ---------------- |
| RecordBeforeSave  | Create           |

### DW - Oportunidade - Espelhar campos da conta

DW - Oportunidade - Espelhar campos da conta {!$Flow.CurrentDateTime}

| Tipo de acionador | Tipo de registro |
| ----------------- | ---------------- |
| RecordBeforeSave  | Create           |

### DW - Oportunidade - Flow After - Avaliar aprovação financeira

Esse fluxo avalie e reavalia a necessidade das aprovação financeira.

| Tipo de acionador | Tipo de registro |
| ----------------- | ---------------- |
| RecordAfterSave   | CreateAndUpdate  |

### DW - Oportunidade - Redefinir Nome

DW - Oportunidade - Redefinir Nome {!$Flow.CurrentDateTime}

| Tipo de acionador | Tipo de registro |
| ----------------- | ---------------- |
| RecordAfterSave   | Update           |

### DW - Oportunidade - Validar limite de crédito de cliente

DW - Oportunidade - Validar limite de crédito de cliente {!$Flow.CurrentDateTime}

| Tipo de acionador | Tipo de registro |
| ----------------- | ---------------- |
| RecordAfterSave   | Update           |

### DW - Oportunidade - Zerar alocações

DW - Oportunidade - Zerar alocações {!$Flow.CurrentDateTime}

| Tipo de acionador | Tipo de registro |
| ----------------- | ---------------- |
| RecordAfterSave   | Update           |

### DW - Opportunity - Flow After - Atribuir empresa no campo lista de opções

DW - Opportunity - Flow After - Atribuir empresa no campo lista de opções {!$Flow.CurrentDateTime}

| Tipo de acionador | Tipo de registro |
| ----------------- | ---------------- |
| RecordAfterSave   | CreateAndUpdate  |

### DW - Opportunity - Flow After - Enviar oportunidade para aprovação automaticamente

DW - Opportunity - Flow After - Enviar oportunidade para aprovação automaticamente {!$Flow.CurrentDateTime}

| Tipo de acionador | Tipo de registro |
| ----------------- | ---------------- |
| RecordAfterSave   | Update           |

### DW - Opportunity - Flow After - Notificar retorno da aprovação financeira

DW - Opportunity - Flow After - Notificar retorno da aprovação financeira {!$Flow.CurrentDateTime}

| Tipo de acionador | Tipo de registro |
| ----------------- | ---------------- |
| RecordAfterSave   | Update           |

### DW - Oportunidade - Notificar retorno da aprovação de serviços

DW - Oportunidade - Notificar retorno da aprovação de serviços {!$Flow.CurrentDateTime}

| Tipo de acionador | Tipo de registro |
| ----------------- | ---------------- |
| RecordAfterSave   | Update           |

### DW - Orquestração - Inserir produtos no orçamento pelo PDF

DW - Orquestração - Inserir produtos no orçamento pelo PDF {!$Flow.CurrentDateTime}

| Tipo de acionador | Tipo de registro |
| ----------------- | ---------------- |
| RecordAfterSave   | CreateAndUpdate  |

### DW - Preenche campo Tipo (Type) na opp

DW - Preenche campo Tipo (Type) na opp {!$Flow.CurrentDateTime}

| Tipo de acionador | Tipo de registro |
| ----------------- | ---------------- |
| RecordBeforeSave  | Create           |

### DW - Preenche endereço pre-definido da opp

DW - Preenche endereço pre-definido da opp {!$Flow.CurrentDateTime}

| Tipo de acionador | Tipo de registro |
| ----------------- | ---------------- |
| RecordBeforeSave  | CreateAndUpdate  |

### Integrar Oportunidade OFI Orcamento

Integrar Oportunidade OFI {!$Flow.CurrentDateTime}

| Tipo de acionador | Tipo de registro |
| ----------------- | ---------------- |
| RecordAfterSave   | Create           |

## Ações Rápidas

| Rótulo                              | Nome de API                           |
| ----------------------------------- | ------------------------------------- |
| Reservar compromisso                | FSL__Book_Appointment                 |
| Candidatos                          | FSL__Candidates                       |
| Caso de devolução                   | Caso_de_devolucao                     |
| Contato                             | Contato                               |
| Criar Caso - Serviço                | CriarCasoServico                      |
| Cliente                             | DWCliente                             |
| Compromisso                         | DWCompromisso                         |
| Vender Peça(s)                      | DWVenderPeca                          |
| Emergência                          | FSL__Emergency                        |
| Iniciar atendimento                 | InciarAtendimento                     |
| Nova conta                          | NewAccount                            |
| Novo contato                        | NewContact                            |
| Novo compromisso                    | FSL__NewEvent                         |
| Novo compromisso                    | NewEvent                              |
| Novo grupo                          | NewGroup                              |
| Nova oportunidade                   | NewOpportunity                        |
| Novo caso                           | NovoCasoServicos                      |
| Novo caso - Serviços                | Novo_caso_servicos                    |
| Email                               | SendEmail                             |
| Alocar peças                        | Opportunity.AlocarPecas               |
| Criar ordem de trabalho             | Opportunity.Criar_ordem_de_trabalho   |
| Criar cotação                       | Opportunity.DWCriarCotacaoBotao       |
| Integrar VEI Veiculo                | Opportunity.DWIntegrarVEIVeiculo      |
| Obter produtos oportunidade clonada | Opportunity.DWObterProdutosOppClonada |
| PDF                                 | Opportunity.DWPDFPropostaOppAtivo     |
| Proposta máquinas                   | Opportunity.DWPDFPropostaOppMaquinas  |
| Proposta oficina                    | Opportunity.DWPDFPropostaOppOficina   |
| Proposta                            | Opportunity.DWPDFPropostas            |
| Romaneio                            | Opportunity.DWRomaneio                |
| Romaneio de devolução               | Opportunity.DWRomaneioDevolucao       |
| Consultar impostos                  | Opportunity.DWSimularimpostos         |
| Clone avançado                      | Opportunity.DW_CloneAvancado          |
| Enviar proposta                     | Opportunity.Enviar_proposta           |
| Integração ERP Peca Balcao          | Opportunity.IntegracaoERPPecaBalcao   |
| Integrar OFI Orçamento              | Opportunity.IntegrarOFIOrcamento      |
| Integrar Frente Caixa OT            | Opportunity.Integrar_Frente_Caixa     |
| Simular impostos                    | Opportunity.Simularimpostos           |
| Solicitar aprovação                 | Opportunity.SolicitarAprovacao        |
| Split oportunidade                  | Opportunity.DW_SPT__SplitOportunidade |
| Publicar                            | FeedItem.TextPost                     |
| Arquivo                             | FeedItem.ContentPost                  |
| Ações inteligentes móveis           | FeedItem.MobileSmartActions           |
| Agradecimento                       | FeedItem.RypplePost                   |
| Link                                | FeedItem.LinkPost                     |
| Pesquisa                            | FeedItem.PollPost                     |
| Pergunta                            | FeedItem.QuestionPost                 |
| Nova nota                           | FeedItem.ContentNote                  |

## Acionadores Apex

### OpportunityTrigger

Status: Active

| Uso                 | Ativo |
| ------------------- | ----- |
| Antes de Inserir    | Não   |
| Depois de Inserir   | Sim   |
| Antes de Atualizar  | Não   |
| Depois de Atualizar | Não   |
| Antes de Excluir    | Não   |
| Depois de Excluir   | Não   |
| Depois de Recuperar | Não   |

# Produto de oportunidade

## Campos

| Rótulo                                  | Nome de API                                 | Tipo      | Ajuda                                                                                                                                                                                                                                                                                                                                                |
| --------------------------------------- | ------------------------------------------- | --------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ID do Item                              | Id                                          | id        | -                                                                                                                                                                                                                                                                                                                                                    |
| ID da oportunidade                      | OpportunityId                               | reference | -                                                                                                                                                                                                                                                                                                                                                    |
| Ordem de classificação                  | SortOrder                                   | int       | -                                                                                                                                                                                                                                                                                                                                                    |
| ID da Entrada da Tabela de Preços       | PricebookEntryId                            | reference | -                                                                                                                                                                                                                                                                                                                                                    |
| ID do produto                           | Product2Id                                  | reference | -                                                                                                                                                                                                                                                                                                                                                    |
| Código do produto                       | ProductCode                                 | string    | -                                                                                                                                                                                                                                                                                                                                                    |
| Nome de produto da oportunidade         | Name                                        | string    | -                                                                                                                                                                                                                                                                                                                                                    |
| Código ISO da moeda                     | CurrencyIsoCode                             | picklist  | -                                                                                                                                                                                                                                                                                                                                                    |
| Quantidade                              | Quantity                                    | double    | -                                                                                                                                                                                                                                                                                                                                                    |
| Desconto                                | Discount                                    | percent   | -                                                                                                                                                                                                                                                                                                                                                    |
| Subtotal                                | Subtotal                                    | currency  | -                                                                                                                                                                                                                                                                                                                                                    |
| Total                                   | TotalPrice                                  | currency  | -                                                                                                                                                                                                                                                                                                                                                    |
| Preço de venda                          | UnitPrice                                   | currency  | -                                                                                                                                                                                                                                                                                                                                                    |
| Custo                                   | ListPrice                                   | currency  | -                                                                                                                                                                                                                                                                                                                                                    |
| Data                                    | ServiceDate                                 | date      | -                                                                                                                                                                                                                                                                                                                                                    |
| Tem agenda de receita                   | HasRevenueSchedule                          | boolean   | -                                                                                                                                                                                                                                                                                                                                                    |
| Tem agenda de quantidade                | HasQuantitySchedule                         | boolean   | -                                                                                                                                                                                                                                                                                                                                                    |
| Descrição da linha                      | Description                                 | string    | -                                                                                                                                                                                                                                                                                                                                                    |
| Tem agenda                              | HasSchedule                                 | boolean   | -                                                                                                                                                                                                                                                                                                                                                    |
| Planejamento de quantidade ativado      | CanUseQuantitySchedule                      | boolean   | -                                                                                                                                                                                                                                                                                                                                                    |
| Planejamento de receita ativado         | CanUseRevenueSchedule                       | boolean   | -                                                                                                                                                                                                                                                                                                                                                    |
| Data de criação                         | CreatedDate                                 | datetime  | -                                                                                                                                                                                                                                                                                                                                                    |
| Criado pelo ID                          | CreatedById                                 | reference | -                                                                                                                                                                                                                                                                                                                                                    |
| Data da última modificação              | LastModifiedDate                            | datetime  | -                                                                                                                                                                                                                                                                                                                                                    |
| Última modificação pelo ID              | LastModifiedById                            | reference | -                                                                                                                                                                                                                                                                                                                                                    |
| Modstamp do sistema                     | SystemModstamp                              | datetime  | -                                                                                                                                                                                                                                                                                                                                                    |
| Excluído                                | IsDeleted                                   | boolean   | -                                                                                                                                                                                                                                                                                                                                                    |
| Data da última visualização             | LastViewedDate                              | datetime  | -                                                                                                                                                                                                                                                                                                                                                    |
| Última data citada                      | LastReferencedDate                          | datetime  | -                                                                                                                                                                                                                                                                                                                                                    |
| Chave do pai                            | DW_NOX__ChavePai__c                         | string    | Campo usado para criação do relacionamento de produto de oportunidade quando inserido pelo NOX.                                                                                                                                                                                                                                                      |
| Chave                                   | DW_NOX__Chave__c                            | string    | Campo de controle para relacionamento de dependência quando inserido pai e filho na mesma operação.                                                                                                                                                                                                                                                  |
| Clonado de                              | DW_NOX__ClonadoDe__c                        | reference | Quando a ação de duplicar é utilizada no NOX, este campo é alimentado automaticamente. Ele pode ser usado em automações fora do pacote.                                                                                                                                                                                                              |
| Estoque                                 | DW_NOX__Estoque__c                          | boolean   | -                                                                                                                                                                                                                                                                                                                                                    |
| Histórico de preços                     | DW_NOX__HistoricoPrecos__c                  | boolean   | Campo de leitura e referência para o componente da tela de oportunidade do NOX                                                                                                                                                                                                                                                                       |
| Id do job                               | DW_NOX__IdJob__c                            | string    | id do job assíncrono que está sendo executado para este registro.                                                                                                                                                                                                                                                                                    |
| Importado pelo NOX?                     | DW_NOX__ImportadoNOX__c                     | boolean   | Verdadeiro quando produto é inserido usando o importador do NOX.                                                                                                                                                                                                                                                                                     |
| Probabilidade de cluster                | DW_NOX__ProbabilidadeCluster__c             | percent   | Este valor é definido quando o cálculo da probabilidade é definido considerando as oportunidade e pedidos do cluster dessa oportunidade. Este cluster é definido pelo administrador.                                                                                                                                                                 |
| Probabilidade de conta                  | DW_NOX__ProbabilidadeConta__c               | percent   | Este valor é definido quando o cálculo da probabilidade é definido considerando apenas as oportunidades e pedidos exclusivo da conta da oportunidade.                                                                                                                                                                                                |
| Probabilidade                           | DW_NOX__Probabilidade__c                    | percent   | Este campo define a média de probabilidade entre a de conta e a de cluster.                                                                                                                                                                                                                                                                          |
| Produto pai                             | DW_NOX__ProdutoPai__c                       | reference | -                                                                                                                                                                                                                                                                                                                                                    |
| Qtde. alocada                           | DW_NOX__QuantidadeReservada__c              | double    | Soma de toda quantidade reservada para este produto.                                                                                                                                                                                                                                                                                                 |
| Requer análise                          | DW_NOX__RequerAnalise__c                    | boolean   | Define se o registro necessita de um processo de análise de preço.                                                                                                                                                                                                                                                                                   |
| Último preço praticado                  | DW_NOX__UltimoPrecoPraticado__c             | currency  | No componente do NOX, na tela de oportunidade, este campo exibirá o preço deste produto na última cotação sincronizada com uma oportunidade ganha.                                                                                                                                                                                                   |
| Últimos pedidos                         | DW_NOX__UltimosPedidos__c                   | boolean   | Campo de leitura e referência para o componente da tela de oportunidade do NOX                                                                                                                                                                                                                                                                       |
| Clonado                                 | DW_NOX__Clonado__c                          | boolean   | Quando a ação de duplicar é utilizada no NOX, este campo é alimentado automaticamente. Ele pode ser usado em automações fora do pacote.                                                                                                                                                                                                              |
| Ativo                                   | Ativo__c                                    | reference | -                                                                                                                                                                                                                                                                                                                                                    |
| Nome produto                            | DW_SPT__DWNomeProdutoPckg__c                | string    | -                                                                                                                                                                                                                                                                                                                                                    |
| Nome produto                            | DW_SPT__DWNomeProduto__c                    | string    | -                                                                                                                                                                                                                                                                                                                                                    |
| Key Split                               | DW_SPT__KeySplitOportunity__c               | string    | -                                                                                                                                                                                                                                                                                                                                                    |
| Família                                 | DWFamilia__c                                | string    | -                                                                                                                                                                                                                                                                                                                                                    |
| Nome                                    | DWNomeProduto__c                            | string    | -                                                                                                                                                                                                                                                                                                                                                    |
| Período do dia solicitado para entrega  | DWPeriodoDiaSolicitadoParaEntrega__c        | picklist  | Este campo pode ser alterado manualmente. Caso o valor do campo Período do dia solicitado para entrega na oportunidade for alterado o valor será propagado para este campo                                                                                                                                                                           |
| Preço de venda unitário com desconto    | DWPrecoVendaComDesconto__c                  | currency  | -                                                                                                                                                                                                                                                                                                                                                    |
| Unidade de medida                       | DWUnidadeMedidaResumo__c                    | string    | -                                                                                                                                                                                                                                                                                                                                                    |
| Necessário aprovação diretor            | NecessarioAprovacaoDiretor__c               | boolean   | Necessário aprovação do diretor quando o desconto for maior ou igual a 5%.                                                                                                                                                                                                                                                                           |
| Status cálculo fator de precificação 10 | StatusCalculoFatorPrecificacao10__c         | picklist  | -                                                                                                                                                                                                                                                                                                                                                    |
| Status cálculo fator de precificação 11 | StatusCalculoFatorPrecificacao11__c         | picklist  | -                                                                                                                                                                                                                                                                                                                                                    |
| Status cálculo fator de precificação 12 | StatusCalculoFatorPrecificacao12__c         | picklist  | -                                                                                                                                                                                                                                                                                                                                                    |
| Status cálculo fator de precificação 13 | StatusCalculoFatorPrecificacao13__c         | picklist  | -                                                                                                                                                                                                                                                                                                                                                    |
| Status cálculo fator de precificação 14 | StatusCalculoFatorPrecificacao14__c         | picklist  | -                                                                                                                                                                                                                                                                                                                                                    |
| Status cálculo fator de precificação 15 | StatusCalculoFatorPrecificacao15__c         | picklist  | -                                                                                                                                                                                                                                                                                                                                                    |
| Status cálculo fator de precificação 16 | StatusCalculoFatorPrecificacao16__c         | picklist  | -                                                                                                                                                                                                                                                                                                                                                    |
| Status cálculo fator de precificação 17 | StatusCalculoFatorPrecificacao17__c         | picklist  | -                                                                                                                                                                                                                                                                                                                                                    |
| Status cálculo fator de precificação 18 | StatusCalculoFatorPrecificacao18__c         | picklist  | -                                                                                                                                                                                                                                                                                                                                                    |
| Status cálculo fator de precificação 19 | StatusCalculoFatorPrecificacao19__c         | picklist  | -                                                                                                                                                                                                                                                                                                                                                    |
| Status cálculo fator de precificação 1  | StatusCalculoFatorPrecificacao1__c          | picklist  | -                                                                                                                                                                                                                                                                                                                                                    |
| Status cálculo fator de precificação 20 | StatusCalculoFatorPrecificacao20__c         | picklist  | -                                                                                                                                                                                                                                                                                                                                                    |
| Status cálculo fator de precificação 21 | StatusCalculoFatorPrecificacao21__c         | picklist  | -                                                                                                                                                                                                                                                                                                                                                    |
| Status cálculo fator de precificação 22 | StatusCalculoFatorPrecificacao22__c         | picklist  | -                                                                                                                                                                                                                                                                                                                                                    |
| Status cálculo fator de precificação 23 | StatusCalculoFatorPrecificacao23__c         | picklist  | -                                                                                                                                                                                                                                                                                                                                                    |
| Status cálculo fator de precificação 24 | StatusCalculoFatorPrecificacao24__c         | picklist  | -                                                                                                                                                                                                                                                                                                                                                    |
| Status cálculo fator de precificação 25 | StatusCalculoFatorPrecificacao25__c         | picklist  | -                                                                                                                                                                                                                                                                                                                                                    |
| Status cálculo fator de precificação 26 | StatusCalculoFatorPrecificacao26__c         | picklist  | -                                                                                                                                                                                                                                                                                                                                                    |
| Status cálculo fator de precificação 27 | StatusCalculoFatorPrecificacao27__c         | picklist  | -                                                                                                                                                                                                                                                                                                                                                    |
| Status cálculo fator de precificação 28 | StatusCalculoFatorPrecificacao28__c         | picklist  | -                                                                                                                                                                                                                                                                                                                                                    |
| Status cálculo fator de precificação 29 | StatusCalculoFatorPrecificacao29__c         | picklist  | -                                                                                                                                                                                                                                                                                                                                                    |
| Status cálculo fator de precificação 2  | StatusCalculoFatorPrecificacao2__c          | picklist  | -                                                                                                                                                                                                                                                                                                                                                    |
| Status cálculo fator de precificação 30 | StatusCalculoFatorPrecificacao30__c         | picklist  | -                                                                                                                                                                                                                                                                                                                                                    |
| Status cálculo fator de precificação 31 | StatusCalculoFatorPrecificacao31__c         | picklist  | -                                                                                                                                                                                                                                                                                                                                                    |
| Status cálculo fator de precificação 32 | StatusCalculoFatorPrecificacao32__c         | picklist  | -                                                                                                                                                                                                                                                                                                                                                    |
| Status cálculo fator de precificação 33 | StatusCalculoFatorPrecificacao33__c         | picklist  | -                                                                                                                                                                                                                                                                                                                                                    |
| Status cálculo fator de precificação 34 | StatusCalculoFatorPrecificacao34__c         | picklist  | -                                                                                                                                                                                                                                                                                                                                                    |
| Status cálculo fator de precificação 35 | StatusCalculoFatorPrecificacao35__c         | picklist  | -                                                                                                                                                                                                                                                                                                                                                    |
| Status cálculo fator de precificação 36 | StatusCalculoFatorPrecificacao36__c         | picklist  | -                                                                                                                                                                                                                                                                                                                                                    |
| Status cálculo fator de precificação 37 | StatusCalculoFatorPrecificacao37__c         | picklist  | -                                                                                                                                                                                                                                                                                                                                                    |
| Status cálculo fator de precificação 38 | StatusCalculoFatorPrecificacao38__c         | picklist  | -                                                                                                                                                                                                                                                                                                                                                    |
| Status cálculo fator de precificação 39 | StatusCalculoFatorPrecificacao39__c         | picklist  | -                                                                                                                                                                                                                                                                                                                                                    |
| Status cálculo fator de precificação 3  | StatusCalculoFatorPrecificacao3__c          | picklist  | -                                                                                                                                                                                                                                                                                                                                                    |
| Status cálculo fator de precificação 4  | StatusCalculoFatorPrecificacao4__c          | picklist  | -                                                                                                                                                                                                                                                                                                                                                    |
| Status cálculo fator de precificação 5  | StatusCalculoFatorPrecificacao5__c          | picklist  | -                                                                                                                                                                                                                                                                                                                                                    |
| Status cálculo fator de precificação 6  | StatusCalculoFatorPrecificacao6__c          | picklist  | -                                                                                                                                                                                                                                                                                                                                                    |
| Status cálculo fator de precificação 7  | StatusCalculoFatorPrecificacao7__c          | picklist  | -                                                                                                                                                                                                                                                                                                                                                    |
| Status cálculo fator de precificação 8  | StatusCalculoFatorPrecificacao8__c          | picklist  | -                                                                                                                                                                                                                                                                                                                                                    |
| Status cálculo fator de precificação 9  | StatusCalculoFatorPrecificacao9__c          | picklist  | -                                                                                                                                                                                                                                                                                                                                                    |
| Imagem                                  | URLExibicao__c                              | string    | -                                                                                                                                                                                                                                                                                                                                                    |
| Alçada do proprietário                  | AlcadaProprietario__c                       | double    | -                                                                                                                                                                                                                                                                                                                                                    |
| Data solicitada para entrega            | DWDataSolicitadaEntrega__c                  | date      | Campo alimentado automaticamente quando "Data solicitada para entrega" na oportunidade é alterada                                                                                                                                                                                                                                                    |
| Descrição do produto                    | DWDescricaoProduto__c                       | textarea  | -                                                                                                                                                                                                                                                                                                                                                    |
| Desvio markup auxiliar                  | DWDesvioMarkupAuxiliar__c                   | percent   | -                                                                                                                                                                                                                                                                                                                                                    |
| % COFINS                                | DWPercentualCOFINS__c                       | percent   | -                                                                                                                                                                                                                                                                                                                                                    |
| % ICMS                                  | DWPercentualICMS__c                         | percent   | Aliquota Interestadual ICMS (4%/7%/12%)                                                                                                                                                                                                                                                                                                              |
| % IPI                                   | DWPercentualIPI__c                          | percent   | -                                                                                                                                                                                                                                                                                                                                                    |
| % PIS                                   | DWPercentualPIS__c                          | percent   | -                                                                                                                                                                                                                                                                                                                                                    |
| % ST                                    | DWPercentualST__c                           | percent   | -                                                                                                                                                                                                                                                                                                                                                    |
| Peso (em quilos)                        | DWPesoEmQuilos__c                           | double    | -                                                                                                                                                                                                                                                                                                                                                    |
| Produto pai                             | DWProdutoPai__c                             | reference | Quando o produto é clonado, este campo faz referência ao produto correspondente da oportunidade pai.                                                                                                                                                                                                                                                 |
| Valor frete total                       | DWValorFreteTotal__c                        | currency  | -                                                                                                                                                                                                                                                                                                                                                    |
| Fator de prec. (valor fixo 21)          | FatorPrecificacao21__c                      | currency  | -                                                                                                                                                                                                                                                                                                                                                    |
| Fator de prec. (valor fixo 22)          | FatorPrecificacao22__c                      | currency  | -                                                                                                                                                                                                                                                                                                                                                    |
| Fator de prec. (valor fixo 23)          | FatorPrecificacao23__c                      | currency  | -                                                                                                                                                                                                                                                                                                                                                    |
| Fator de prec. (valor fixo 24)          | FatorPrecificacao24__c                      | currency  | -                                                                                                                                                                                                                                                                                                                                                    |
| Fator de prec. (valor fixo 25)          | FatorPrecificacao25__c                      | currency  | -                                                                                                                                                                                                                                                                                                                                                    |
| Fator de prec. (valor fixo 26)          | FatorPrecificacao26__c                      | currency  | -                                                                                                                                                                                                                                                                                                                                                    |
| Fator de prec. (valor fixo 27)          | FatorPrecificacao27__c                      | currency  | -                                                                                                                                                                                                                                                                                                                                                    |
| Fator de prec. (valor fixo 28)          | FatorPrecificacao28__c                      | currency  | -                                                                                                                                                                                                                                                                                                                                                    |
| Fator de prec. (valor fixo 29)          | FatorPrecificacao29__c                      | currency  | -                                                                                                                                                                                                                                                                                                                                                    |
| Fator de prec. (valor fixo 30)          | FatorPrecificacao30__c                      | currency  | -                                                                                                                                                                                                                                                                                                                                                    |
| Fator de prec. (valor fixo 31)          | FatorPrecificacao31__c                      | currency  | -                                                                                                                                                                                                                                                                                                                                                    |
| Fator de prec. (valor fixo 32)          | FatorPrecificacao32__c                      | currency  | -                                                                                                                                                                                                                                                                                                                                                    |
| Fator de prec. (valor fixo 33)          | FatorPrecificacao33__c                      | currency  | -                                                                                                                                                                                                                                                                                                                                                    |
| Fator de prec. (valor fixo 34)          | FatorPrecificacao34__c                      | currency  | -                                                                                                                                                                                                                                                                                                                                                    |
| Fator de prec. (valor fixo 35)          | FatorPrecificacao35__c                      | currency  | -                                                                                                                                                                                                                                                                                                                                                    |
| Fator de prec. (valor fixo 36)          | FatorPrecificacao36__c                      | currency  | -                                                                                                                                                                                                                                                                                                                                                    |
| Fator de prec. (valor fixo 37)          | FatorPrecificacao37__c                      | currency  | -                                                                                                                                                                                                                                                                                                                                                    |
| Fator de prec. (valor fixo 38)          | FatorPrecificacao38__c                      | currency  | -                                                                                                                                                                                                                                                                                                                                                    |
| Fator de prec. (valor fixo 39)          | FatorPrecificacao39__c                      | currency  | -                                                                                                                                                                                                                                                                                                                                                    |
| Fator de prec. (coeficiente 10)         | FatorPrecificacaoCoeficiente10__c           | percent   | -                                                                                                                                                                                                                                                                                                                                                    |
| Fator de prec. (coeficiente 11)         | FatorPrecificacaoCoeficiente11__c           | percent   | -                                                                                                                                                                                                                                                                                                                                                    |
| Fator de prec. (coeficiente 12)         | FatorPrecificacaoCoeficiente12__c           | percent   | -                                                                                                                                                                                                                                                                                                                                                    |
| Fator de prec. (coeficiente 13)         | FatorPrecificacaoCoeficiente13__c           | percent   | -                                                                                                                                                                                                                                                                                                                                                    |
| Fator de prec. (coeficiente 14)         | FatorPrecificacaoCoeficiente14__c           | percent   | -                                                                                                                                                                                                                                                                                                                                                    |
| Fator de prec. (coeficiente 15)         | FatorPrecificacaoCoeficiente15__c           | percent   | -                                                                                                                                                                                                                                                                                                                                                    |
| Fator de prec. (coeficiente 16)         | FatorPrecificacaoCoeficiente16__c           | percent   | -                                                                                                                                                                                                                                                                                                                                                    |
| Fator de prec. (coeficiente 17)         | FatorPrecificacaoCoeficiente17__c           | percent   | -                                                                                                                                                                                                                                                                                                                                                    |
| Fator de prec. (coeficiente 18)         | FatorPrecificacaoCoeficiente18__c           | percent   | -                                                                                                                                                                                                                                                                                                                                                    |
| Alçada n1                               | FatorPrecificacaoCoeficiente19__c           | percent   | -                                                                                                                                                                                                                                                                                                                                                    |
| Fator de prec. (comissão)               | FatorPrecificacaoCoeficiente1__c            | percent   | -                                                                                                                                                                                                                                                                                                                                                    |
| Alçada n2                               | FatorPrecificacaoCoeficiente20__c           | percent   | -                                                                                                                                                                                                                                                                                                                                                    |
| Fator de prec. (Condição de pagamento)  | FatorPrecificacaoCoeficiente2__c            | percent   | -                                                                                                                                                                                                                                                                                                                                                    |
| Fator de prec. (contrato)               | FatorPrecificacaoCoeficiente3__c            | percent   | -                                                                                                                                                                                                                                                                                                                                                    |
| Fator de prec. (desconto)               | FatorPrecificacaoCoeficiente4__c            | percent   | -                                                                                                                                                                                                                                                                                                                                                    |
| Fator de prec. (campanha)               | FatorPrecificacaoCoeficiente5__c            | percent   | -                                                                                                                                                                                                                                                                                                                                                    |
| Fator de prec. (trans. frete)           | FatorPrecificacaoCoeficiente6__c            | percent   | -                                                                                                                                                                                                                                                                                                                                                    |
| Markup planejado %                      | FatorPrecificacaoCoeficiente7__c            | percent   | -                                                                                                                                                                                                                                                                                                                                                    |
| Fator de prec. (forma de pagamento)     | FatorPrecificacaoCoeficiente8__c            | percent   | -                                                                                                                                                                                                                                                                                                                                                    |
| Fator de prec. (coeficiente 9)          | FatorPrecificacaoCoeficiente9__c            | percent   | -                                                                                                                                                                                                                                                                                                                                                    |
| Código externo do produto               | DWCodigoExternoProduto__c                   | string    | -                                                                                                                                                                                                                                                                                                                                                    |
| Custo realizado total                   | DWCustoRealizadoTotal__c                    | currency  | -                                                                                                                                                                                                                                                                                                                                                    |
| Custo realizado unidade                 | DWCustoRealizadoUnitario__c                 | currency  | -                                                                                                                                                                                                                                                                                                                                                    |
| Desvio de margem                        | DWDesvioMarkupEscala__c                     | string    | -                                                                                                                                                                                                                                                                                                                                                    |
| Desvio de margem                        | DWDesvioMarkup__c                           | percent   | -                                                                                                                                                                                                                                                                                                                                                    |
| Margem bruta                            | DWMargemBruta__c                            | percent   | -                                                                                                                                                                                                                                                                                                                                                    |
| Margem líquida                          | DWMargemLiquida__c                          | percent   | Lucro bruto                                                                                                                                                                                                                                                                                                                                          |
| Markup realizado %                      | DWMarkupRealizado__c                        | percent   | -                                                                                                                                                                                                                                                                                                                                                    |
| Preço de lista + markup (V2)            | DWPrecoListaPlusMarkup__c                   | currency  | -                                                                                                                                                                                                                                                                                                                                                    |
| Preço de venda com desconto - custos    | DWPrecoVendaComDescontoMenosCustos__c       | currency  | -                                                                                                                                                                                                                                                                                                                                                    |
| Resultado financeiro total              | DWResultadoFinanceiroTotal__c               | currency  | -                                                                                                                                                                                                                                                                                                                                                    |
| Resultado financeiro unidade            | DWResultadoFinanceiroUnidade__c             | currency  | -                                                                                                                                                                                                                                                                                                                                                    |
| Valor frete unidade                     | DWValorFreteUnidade__c                      | currency  | -                                                                                                                                                                                                                                                                                                                                                    |
| Flag Aprovação                          | FlagAprovacao__c                            | string    | -                                                                                                                                                                                                                                                                                                                                                    |
| Necessário aprovação gerente            | NecessarioAprovacaoGerente__c               | boolean   | Necessário aprovação do gerente quando o desconto for maior ou igual a 2%.                                                                                                                                                                                                                                                                           |
| Codigo Externo                          | DWCodigoExterno__c                          | string    | -                                                                                                                                                                                                                                                                                                                                                    |
| Quantidade BO Transporte                | DWQuantidadeBOTransporte__c                 | double    | -                                                                                                                                                                                                                                                                                                                                                    |
| Quantidade Baixada                      | DWQuantidadeBaixada__c                      | double    | -                                                                                                                                                                                                                                                                                                                                                    |
| Quantidade Vinculada                    | DWQuantidadeVinculada__c                    | double    | -                                                                                                                                                                                                                                                                                                                                                    |
| Simular impostos                        | DWSimularImpostos__c                        | picklist  | -                                                                                                                                                                                                                                                                                                                                                    |
| Tipo do item                            | DWTipoItem__c                               | picklist  | -                                                                                                                                                                                                                                                                                                                                                    |
| Quantidade faltante                     | DWQuantidadeFaltante__c                     | double    | Indica quantos itens faltam ser consumidos do estoque.                                                                                                                                                                                                                                                                                               |
| Percentual de desconto do resumo        | DW_NPX__DescontoResumo__c                   | percent   | -                                                                                                                                                                                                                                                                                                                                                    |
| Percentual de desconto                  | DW_NPX__Desconto__c                         | percent   | -                                                                                                                                                                                                                                                                                                                                                    |
| FP. 21 - Correção de serviço            | DW_NPX__FatorPrecificacao21__c              | currency  | -                                                                                                                                                                                                                                                                                                                                                    |
| Fator de prec. (valor fixo 22)          | DW_NPX__FatorPrecificacao22__c              | currency  | -                                                                                                                                                                                                                                                                                                                                                    |
| Fator de prec. (valor fixo 23)          | DW_NPX__FatorPrecificacao23__c              | currency  | -                                                                                                                                                                                                                                                                                                                                                    |
| Fator de prec. (valor fixo 24)          | DW_NPX__FatorPrecificacao24__c              | currency  | -                                                                                                                                                                                                                                                                                                                                                    |
| Fator de prec. (valor fixo 25)          | DW_NPX__FatorPrecificacao25__c              | currency  | -                                                                                                                                                                                                                                                                                                                                                    |
| Fator de prec. (valor fixo 26)          | DW_NPX__FatorPrecificacao26__c              | currency  | -                                                                                                                                                                                                                                                                                                                                                    |
| Fator de prec. (valor fixo 27)          | DW_NPX__FatorPrecificacao27__c              | currency  | -                                                                                                                                                                                                                                                                                                                                                    |
| Fator de prec. (valor fixo 28)          | DW_NPX__FatorPrecificacao28__c              | currency  | -                                                                                                                                                                                                                                                                                                                                                    |
| Fator de prec. (valor fixo 29)          | DW_NPX__FatorPrecificacao29__c              | currency  | -                                                                                                                                                                                                                                                                                                                                                    |
| Fator de prec. (valor fixo 30)          | DW_NPX__FatorPrecificacao30__c              | currency  | -                                                                                                                                                                                                                                                                                                                                                    |
| Fator de prec. (valor fixo 31)          | DW_NPX__FatorPrecificacao31__c              | currency  | -                                                                                                                                                                                                                                                                                                                                                    |
| Fator de prec. (valor fixo 32)          | DW_NPX__FatorPrecificacao32__c              | currency  | -                                                                                                                                                                                                                                                                                                                                                    |
| Fator de prec. (valor fixo 33)          | DW_NPX__FatorPrecificacao33__c              | currency  | -                                                                                                                                                                                                                                                                                                                                                    |
| Fator de prec. (valor fixo 34)          | DW_NPX__FatorPrecificacao34__c              | currency  | -                                                                                                                                                                                                                                                                                                                                                    |
| Fator de prec. (valor fixo 35)          | DW_NPX__FatorPrecificacao35__c              | currency  | -                                                                                                                                                                                                                                                                                                                                                    |
| Fator de prec. (valor fixo 36)          | DW_NPX__FatorPrecificacao36__c              | currency  | -                                                                                                                                                                                                                                                                                                                                                    |
| Fator de prec. (valor fixo 37)          | DW_NPX__FatorPrecificacao37__c              | currency  | -                                                                                                                                                                                                                                                                                                                                                    |
| Fator de prec. (valor fixo 38)          | DW_NPX__FatorPrecificacao38__c              | currency  | -                                                                                                                                                                                                                                                                                                                                                    |
| Fator de prec. (valor fixo 39)          | DW_NPX__FatorPrecificacao39__c              | currency  | -                                                                                                                                                                                                                                                                                                                                                    |
| Fator de prec. (coeficiente 10)         | DW_NPX__FatorPrecificacaoCoeficiente10__c   | percent   | -                                                                                                                                                                                                                                                                                                                                                    |
| Fator de prec. (coeficiente 11)         | DW_NPX__FatorPrecificacaoCoeficiente11__c   | percent   | -                                                                                                                                                                                                                                                                                                                                                    |
| Fator de prec. (coeficiente 12)         | DW_NPX__FatorPrecificacaoCoeficiente12__c   | percent   | -                                                                                                                                                                                                                                                                                                                                                    |
| Fator de prec. (coeficiente 13)         | DW_NPX__FatorPrecificacaoCoeficiente13__c   | percent   | -                                                                                                                                                                                                                                                                                                                                                    |
| Fator de prec. (coeficiente 14)         | DW_NPX__FatorPrecificacaoCoeficiente14__c   | percent   | -                                                                                                                                                                                                                                                                                                                                                    |
| Fator de prec. (coeficiente 15)         | DW_NPX__FatorPrecificacaoCoeficiente15__c   | percent   | -                                                                                                                                                                                                                                                                                                                                                    |
| Fator de prec. (coeficiente 16)         | DW_NPX__FatorPrecificacaoCoeficiente16__c   | percent   | -                                                                                                                                                                                                                                                                                                                                                    |
| Fator de prec. (coeficiente 17)         | DW_NPX__FatorPrecificacaoCoeficiente17__c   | percent   | -                                                                                                                                                                                                                                                                                                                                                    |
| Fator de prec. (coeficiente 18)         | DW_NPX__FatorPrecificacaoCoeficiente18__c   | percent   | -                                                                                                                                                                                                                                                                                                                                                    |
| FP. 19 - Alçada Nº 1                    | DW_NPX__FatorPrecificacaoCoeficiente19__c   | percent   | -                                                                                                                                                                                                                                                                                                                                                    |
| FP. 01 - ICMS %                         | DW_NPX__FatorPrecificacaoCoeficiente1__c    | percent   | -                                                                                                                                                                                                                                                                                                                                                    |
| FP. 20 - Alçada Nº 2                    | DW_NPX__FatorPrecificacaoCoeficiente20__c   | percent   | -                                                                                                                                                                                                                                                                                                                                                    |
| FP. 02 - IPI %                          | DW_NPX__FatorPrecificacaoCoeficiente2__c    | percent   | -                                                                                                                                                                                                                                                                                                                                                    |
| FP. 03 - PIS %                          | DW_NPX__FatorPrecificacaoCoeficiente3__c    | percent   | -                                                                                                                                                                                                                                                                                                                                                    |
| FP. 04 - COFINS %                       | DW_NPX__FatorPrecificacaoCoeficiente4__c    | percent   | -                                                                                                                                                                                                                                                                                                                                                    |
| FP. 05 - ST %                           | DW_NPX__FatorPrecificacaoCoeficiente5__c    | percent   | -                                                                                                                                                                                                                                                                                                                                                    |
| Fator de prec. (trans. frete)           | DW_NPX__FatorPrecificacaoCoeficiente6__c    | percent   | -                                                                                                                                                                                                                                                                                                                                                    |
| FP. 07 - Markup %                       | DW_NPX__FatorPrecificacaoCoeficiente7__c    | percent   | -                                                                                                                                                                                                                                                                                                                                                    |
| Fator de prec. (forma de pagamento)     | DW_NPX__FatorPrecificacaoCoeficiente8__c    | percent   | -                                                                                                                                                                                                                                                                                                                                                    |
| Fator de prec. (coeficiente 9)          | DW_NPX__FatorPrecificacaoCoeficiente9__c    | percent   | -                                                                                                                                                                                                                                                                                                                                                    |
| Id do job do NPX                        | DW_NPX__IdJobNPX__c                         | string    | Este campo é preenchido quando o NPX está calculando o cálculo do desconto horizontal de maneira assíncrona.                                                                                                                                                                                                                                         |
| JSON de modelador                       | DW_NPX__JSONModelador__c                    | textarea  | JSON de como o preço de venda foi modelado. Campo atribuído na criação do produto de oportunidade.                                                                                                                                                                                                                                                   |
| Montante de desconto do resumo          | DW_NPX__MontanteDescontoResumo__c           | currency  | -                                                                                                                                                                                                                                                                                                                                                    |
| Montante de desconto                    | DW_NPX__MontanteDesconto__c                 | currency  | Desconto em moeda provido pelo processo do NPX.                                                                                                                                                                                                                                                                                                      |
| Saving permitido                        | DW_NPX__SavingPermitido__c                  | percent   | Define o valor máximo de saving que pode ser utilizado neste produto de oportunidade. Este valor é calculado de acordo com os qualificadores do catálogo de preços.                                                                                                                                                                                  |
| Saving utilizado                        | DW_NPX__SavingUtilizado__c                  | percent   | Define o valor do saving utilizado deste produto. A validação deste valor deve ser feita em um processo fora do NPX.                                                                                                                                                                                                                                 |
| Status cálculo fator de precificação 10 | DW_NPX__StatusCalculoFatorPrecificacao10__c | picklist  | -                                                                                                                                                                                                                                                                                                                                                    |
| Status cálculo fator de precificação 11 | DW_NPX__StatusCalculoFatorPrecificacao11__c | picklist  | -                                                                                                                                                                                                                                                                                                                                                    |
| Status cálculo fator de precificação 12 | DW_NPX__StatusCalculoFatorPrecificacao12__c | picklist  | -                                                                                                                                                                                                                                                                                                                                                    |
| Status cálculo fator de precificação 13 | DW_NPX__StatusCalculoFatorPrecificacao13__c | picklist  | -                                                                                                                                                                                                                                                                                                                                                    |
| Status cálculo fator de precificação 14 | DW_NPX__StatusCalculoFatorPrecificacao14__c | picklist  | -                                                                                                                                                                                                                                                                                                                                                    |
| Status cálculo fator de precificação 15 | DW_NPX__StatusCalculoFatorPrecificacao15__c | picklist  | -                                                                                                                                                                                                                                                                                                                                                    |
| Status cálculo fator de precificação 16 | DW_NPX__StatusCalculoFatorPrecificacao16__c | picklist  | -                                                                                                                                                                                                                                                                                                                                                    |
| Status cálculo fator de precificação 17 | DW_NPX__StatusCalculoFatorPrecificacao17__c | picklist  | -                                                                                                                                                                                                                                                                                                                                                    |
| Status cálculo fator de precificação 18 | DW_NPX__StatusCalculoFatorPrecificacao18__c | picklist  | -                                                                                                                                                                                                                                                                                                                                                    |
| Status FP. 19                           | DW_NPX__StatusCalculoFatorPrecificacao19__c | picklist  | -                                                                                                                                                                                                                                                                                                                                                    |
| Status cálculo fator de precificação 1  | DW_NPX__StatusCalculoFatorPrecificacao1__c  | picklist  | -                                                                                                                                                                                                                                                                                                                                                    |
| Status FP. 20                           | DW_NPX__StatusCalculoFatorPrecificacao20__c | picklist  | -                                                                                                                                                                                                                                                                                                                                                    |
| Status cálculo fator de precificação 21 | DW_NPX__StatusCalculoFatorPrecificacao21__c | picklist  | -                                                                                                                                                                                                                                                                                                                                                    |
| Status cálculo fator de precificação 22 | DW_NPX__StatusCalculoFatorPrecificacao22__c | picklist  | -                                                                                                                                                                                                                                                                                                                                                    |
| Status cálculo fator de precificação 23 | DW_NPX__StatusCalculoFatorPrecificacao23__c | picklist  | -                                                                                                                                                                                                                                                                                                                                                    |
| Status cálculo fator de precificação 24 | DW_NPX__StatusCalculoFatorPrecificacao24__c | picklist  | -                                                                                                                                                                                                                                                                                                                                                    |
| Status cálculo fator de precificação 25 | DW_NPX__StatusCalculoFatorPrecificacao25__c | picklist  | -                                                                                                                                                                                                                                                                                                                                                    |
| Status cálculo fator de precificação 26 | DW_NPX__StatusCalculoFatorPrecificacao26__c | picklist  | -                                                                                                                                                                                                                                                                                                                                                    |
| Status cálculo fator de precificação 27 | DW_NPX__StatusCalculoFatorPrecificacao27__c | picklist  | -                                                                                                                                                                                                                                                                                                                                                    |
| Status cálculo fator de precificação 28 | DW_NPX__StatusCalculoFatorPrecificacao28__c | picklist  | -                                                                                                                                                                                                                                                                                                                                                    |
| Status cálculo fator de precificação 29 | DW_NPX__StatusCalculoFatorPrecificacao29__c | picklist  | -                                                                                                                                                                                                                                                                                                                                                    |
| Status cálculo fator de precificação 2  | DW_NPX__StatusCalculoFatorPrecificacao2__c  | picklist  | -                                                                                                                                                                                                                                                                                                                                                    |
| Status cálculo fator de precificação 30 | DW_NPX__StatusCalculoFatorPrecificacao30__c | picklist  | -                                                                                                                                                                                                                                                                                                                                                    |
| Status cálculo fator de precificação 31 | DW_NPX__StatusCalculoFatorPrecificacao31__c | picklist  | -                                                                                                                                                                                                                                                                                                                                                    |
| Status cálculo fator de precificação 32 | DW_NPX__StatusCalculoFatorPrecificacao32__c | picklist  | -                                                                                                                                                                                                                                                                                                                                                    |
| Status cálculo fator de precificação 33 | DW_NPX__StatusCalculoFatorPrecificacao33__c | picklist  | -                                                                                                                                                                                                                                                                                                                                                    |
| Status cálculo fator de precificação 34 | DW_NPX__StatusCalculoFatorPrecificacao34__c | picklist  | -                                                                                                                                                                                                                                                                                                                                                    |
| Status cálculo fator de precificação 35 | DW_NPX__StatusCalculoFatorPrecificacao35__c | picklist  | -                                                                                                                                                                                                                                                                                                                                                    |
| Status cálculo fator de precificação 36 | DW_NPX__StatusCalculoFatorPrecificacao36__c | picklist  | -                                                                                                                                                                                                                                                                                                                                                    |
| Status cálculo fator de precificação 37 | DW_NPX__StatusCalculoFatorPrecificacao37__c | picklist  | -                                                                                                                                                                                                                                                                                                                                                    |
| Status cálculo fator de precificação 38 | DW_NPX__StatusCalculoFatorPrecificacao38__c | picklist  | -                                                                                                                                                                                                                                                                                                                                                    |
| Status cálculo fator de precificação 39 | DW_NPX__StatusCalculoFatorPrecificacao39__c | picklist  | -                                                                                                                                                                                                                                                                                                                                                    |
| Status cálculo fator de precificação 3  | DW_NPX__StatusCalculoFatorPrecificacao3__c  | picklist  | -                                                                                                                                                                                                                                                                                                                                                    |
| Status cálculo fator de precificação 4  | DW_NPX__StatusCalculoFatorPrecificacao4__c  | picklist  | -                                                                                                                                                                                                                                                                                                                                                    |
| Status cálculo fator de precificação 5  | DW_NPX__StatusCalculoFatorPrecificacao5__c  | picklist  | -                                                                                                                                                                                                                                                                                                                                                    |
| Status cálculo fator de precificação 6  | DW_NPX__StatusCalculoFatorPrecificacao6__c  | picklist  | -                                                                                                                                                                                                                                                                                                                                                    |
| Status FP. 07                           | DW_NPX__StatusCalculoFatorPrecificacao7__c  | picklist  | -                                                                                                                                                                                                                                                                                                                                                    |
| Status cálculo fator de precificação 8  | DW_NPX__StatusCalculoFatorPrecificacao8__c  | picklist  | -                                                                                                                                                                                                                                                                                                                                                    |
| Status cálculo fator de precificação 9  | DW_NPX__StatusCalculoFatorPrecificacao9__c  | picklist  | -                                                                                                                                                                                                                                                                                                                                                    |
| Calcula PIS e COFINS                    | CalculaPISCOFINS__c                         | string    | -                                                                                                                                                                                                                                                                                                                                                    |
| Base PIS                                | BasePIS__c                                  | string    | -                                                                                                                                                                                                                                                                                                                                                    |
| Base COFINS                             | BaseCOFINS__c                               | string    | -                                                                                                                                                                                                                                                                                                                                                    |
| Cod operação fiscal                     | CodOperacaoFiscal__c                        | string    | -                                                                                                                                                                                                                                                                                                                                                    |
| Bônus max fábrica (%)                   | DWBonusMaxFabrica__c                        | percent   | -                                                                                                                                                                                                                                                                                                                                                    |
| Margem max bônus fábrica                | DWMargemMaxBonusFabrica__c                  | percent   | -                                                                                                                                                                                                                                                                                                                                                    |
| Bônus fábrica (R$)                      | DWBonusFabricaVarForm__c                    | currency  | -                                                                                                                                                                                                                                                                                                                                                    |
| Margem bruta c/ bônus                   | DWMargemBrutaBonus__c                       | percent   | -                                                                                                                                                                                                                                                                                                                                                    |
| Qtde. alocada inicial                   | DWQtdReservadaAnteriormente__c              | double    | Cópia do valor anterior do campo de quantidade reservada.                                                                                                                                                                                                                                                                                            |
| Código exclusivo peca balcao            | CodigoExclusivoPecaBalcao__c                | string    | -                                                                                                                                                                                                                                                                                                                                                    |
| Status integração                       | StatusIntegracaoPeca__c                     | picklist  | -                                                                                                                                                                                                                                                                                                                                                    |
| ICMS Retido                             | DWICMSRetido__c                             | percent   | -                                                                                                                                                                                                                                                                                                                                                    |
| ICMS Retido - ST                        | ICMSRetidoST__c                             | string    | -                                                                                                                                                                                                                                                                                                                                                    |
| Custo + Markup + Frete + Despesas (V3)  | DWCustoMarkupFrete__c                       | currency  | -                                                                                                                                                                                                                                                                                                                                                    |
| % ICMS (Origem)                         | DWICMSPercUFOrigem__c                       | percent   | Aliquota Interestadual ICMS (4%/7%/12%)                                                                                                                                                                                                                                                                                                              |
| ICMS unitário realizado                 | DWICMSUnitario__c                           | currency  | DWPrecoVendaComDesconto__c * DWPercentualICMS__c                                                                                                                                                                                                                                                                                                     |
| Oportunidade ganha                      | DWOportunidadeGanha__c                      | boolean   | -                                                                                                                                                                                                                                                                                                                                                    |
| Base ICMS V3 & PISCO (V4)               | DWBaseICMSV3PlusPISCOV4__c                  | currency  | (DWCustoMarkupFrete__c
/ (
   1 
   - ((IF(ISBLANK(DWPercentualPIS__c), 0, DWPercentualPIS__c) + IF(ISBLANK(DWPercentualCOFINS__c), 0,DWPercentualCOFINS__c)))
))

-

((DWCustoMarkupFrete__c
/ (
   1 
   - ((IF(ISBLANK(DWPercentualPIS__c), 0, DWPercentualPIS__c) + IF(ISBLANK(DWPercentualCOFINS__c), 0,DWPercentualCOFINS__c)))
))* Discount ) |
| Base ST                                 | DWBaseST__c                                 | currency  | -                                                                                                                                                                                                                                                                                                                                                    |
| COFINS unitário                         | DWCOFINSUnitario__c                         | currency  | -                                                                                                                                                                                                                                                                                                                                                    |
| PIS unitário (R$)                       | DWPIS__c                                    | currency  | -                                                                                                                                                                                                                                                                                                                                                    |
| Preço V3 + Impostos (V4)                | DWPrecoPlusImpostosV4__c                    | currency  | -                                                                                                                                                                                                                                                                                                                                                    |
| Receita líquida unitária                | DWReceitaLquidaUnitaria__c                  | currency  | -                                                                                                                                                                                                                                                                                                                                                    |
| Valor de impostos unitário              | DWValorImpostosUnitario__c                  | currency  | -                                                                                                                                                                                                                                                                                                                                                    |
| DIFAL (Antecipação)                     | DWDIFALAntecipacao__c                       | currency  | -                                                                                                                                                                                                                                                                                                                                                    |
| N Seq  Romaneio                         | NSeqRomaneio__c                             | string    | -                                                                                                                                                                                                                                                                                                                                                    |
| Compromisso de serviço                  | DWCompromissoServico__c                     | reference | -                                                                                                                                                                                                                                                                                                                                                    |
| Criado via automação                    | DWCriadoAutomacao__c                        | boolean   | -                                                                                                                                                                                                                                                                                                                                                    |
| Código                                  | DWCodigoEmail__c                            | string    | -                                                                                                                                                                                                                                                                                                                                                    |
| Código Email                            | DWCodigoEmail2__c                           | string    | -                                                                                                                                                                                                                                                                                                                                                    |
| NCM                                     | DWNCM__c                                    | string    | -                                                                                                                                                                                                                                                                                                                                                    |
| ICMS total                              | DWICMSTotal__c                              | currency  | -                                                                                                                                                                                                                                                                                                                                                    |
| Valor do desconto                       | DWValorDesconto__c                          | currency  | -                                                                                                                                                                                                                                                                                                                                                    |
| Perc. desc. aplicado fábrica            | DWDescSugeridoFabrica__c                    | percent   | -                                                                                                                                                                                                                                                                                                                                                    |
| Fazer alocação de estoque?              | DWFazerAlocacaoEstoque__c                   | boolean   | -                                                                                                                                                                                                                                                                                                                                                    |
| Ignorar alocação?                       | DWIgnorarReserva__c                         | boolean   | -                                                                                                                                                                                                                                                                                                                                                    |
| Ordem de trabalho                       | DWOrdemTrabalho__c                          | reference | -                                                                                                                                                                                                                                                                                                                                                    |
| Preço + Imp. Rec. Bruta (V5)            | DWPrecoPlusImpostosV5__c                    | currency  | Preço + Imposto (Receita bruta planejada) - V5                                                                                                                                                                                                                                                                                                       |
| Preço sugerido                          | DWPrecoSugerido__c                          | currency  | -                                                                                                                                                                                                                                                                                                                                                    |
| Negociado                               | DWPrecoVenda__c                             | currency  | -                                                                                                                                                                                                                                                                                                                                                    |
| Prateleira                              | Prateleira__c                               | string    | -                                                                                                                                                                                                                                                                                                                                                    |
| Estante                                 | Estante__c                                  | string    | -                                                                                                                                                                                                                                                                                                                                                    |
| Rua                                     | Rua__c                                      | string    | -                                                                                                                                                                                                                                                                                                                                                    |
| Zona                                    | Zona__c                                     | string    | -                                                                                                                                                                                                                                                                                                                                                    |
| Quantidade devolvida                    | DWQuantidadeDevolvida__c                    | double    | -                                                                                                                                                                                                                                                                                                                                                    |
| É serviço                               | DWServico__c                                | boolean   | -                                                                                                                                                                                                                                                                                                                                                    |
| Possui substituto                       | DWPossuiSubstituto__c                       | boolean   | -                                                                                                                                                                                                                                                                                                                                                    |
| Total peça                              | DWTotalPeca__c                              | currency  | -                                                                                                                                                                                                                                                                                                                                                    |
| Total serviço                           | DWTotalServico__c                           | currency  | -                                                                                                                                                                                                                                                                                                                                                    |
| Quantidade reservada original           | DWQuantidadeReservadaOriginal__c            | double    | -                                                                                                                                                                                                                                                                                                                                                    |

## Relacionamentos Filhos

| Rótulo                         | Nome de relacionamento         | Campo de referência            | Objeto Relacionado                    |
| ------------------------------ | ------------------------------ | ------------------------------ | ------------------------------------- |
| AIInsightValue                 | -                              | SobjectLookupValueId           | AIInsightValue                        |
| AIRecordInsight                | -                              | TargetId                       | AIRecordInsight                       |
| FatoresPrecificacao__r         | FatoresPrecificacao__r         | ProdutoOportunidade__c         | DWAplicacaoFatorPrecificacao__c       |
| DW_NOX__ReservasEstoque__r     | DW_NOX__ReservasEstoque__r     | DW_NOX__ProdutoOportunidade__c | DW_NOX__ReservaEstoque__c             |
| DW_NPX__FatoresPrecificacao__r | DW_NPX__FatoresPrecificacao__r | DW_NPX__ProdutoOportunidade__c | DW_NPX__AplicacaoFatorPrecificacao__c |
| FlowExecutionErrorEvent        | -                              | ContextRecordId                | FlowExecutionErrorEvent               |
| FlowRecordRelation             | -                              | RelatedRecordId                | FlowRecordRelation                    |
| ForecastingFact                | -                              | ForecastedObjectId             | ForecastingFact                       |
| Http_Request_Logs__r           | Http_Request_Logs__r           | Produto_de_oportunidade__c     | HttpRequestLog__c                     |
| DWProdutoOportunidade__r       | DWProdutoOportunidade__r       | DWProdutoPai__c                | OpportunityLineItem                   |
| DW_NOX__Clonados__r            | DW_NOX__Clonados__r            | DW_NOX__ClonadoDe__c           | OpportunityLineItem                   |
| DW_NOX__ProdutoOportunidade__r | DW_NOX__ProdutoOportunidade__r | DW_NOX__ProdutoPai__c          | OpportunityLineItem                   |
| OpportunityLineItemSchedules   | OpportunityLineItemSchedules   | OpportunityLineItemId          | OpportunityLineItemSchedule           |
| OpportunityLineItemSplits      | OpportunityLineItemSplits      | OpportunityLineItemId          | OpportunityLineItemSplit              |
| Produtos_consumidos__r         | Produtos_consumidos__r         | ProdutoOportunidade__c         | ProductConsumed                       |
| QuoteLineItem                  | -                              | OpportunityLineItemId          | QuoteLineItem                         |
| QuoteLineItemChangeEvent       | -                              | OpportunityLineItemId          | QuoteLineItemChangeEvent              |

## Acionadores de Fluxo

### DW - Calcula peso do produto da oportunidade

DW - Calcula peso do produto da oportunidade {!$Flow.CurrentDateTime}

| Tipo de acionador | Tipo de registro |
| ----------------- | ---------------- |
| RecordBeforeSave  | CreateAndUpdate  |

### DW Calculo Impostos

DW {!$Flow.CurrentDateTime}

| Tipo de acionador | Tipo de registro |
| ----------------- | ---------------- |
| RecordAfterSave   | Create           |

### DW - Recálculo de preço de venda - Mercadão

DW - Recálculo de preço de venda - Mercadão {!$Flow.CurrentDateTime}

| Tipo de acionador | Tipo de registro |
| ----------------- | ---------------- |
| RecordAfterSave   | CreateAndUpdate  |

### DW - Forçar desconto conforme preço sugerido na entrada de catalogo

DW - Forçar desconto conforme preço sugerido na entrada de catalogo {!$Flow.CurrentDateTime}

| Tipo de acionador | Tipo de registro |
| ----------------- | ---------------- |
| RecordAfterSave   | CreateAndUpdate  |

### DW | NOX | Set quantity by correction factor

Este fluxo define a quantidade de acordo com o fator de correção de produto. Só é executado quando fator de correção foi definido maior que zero.

| Tipo de acionador | Tipo de registro |
| ----------------- | ---------------- |
| RecordAfterSave   | CreateAndUpdate  |

### DW NPX | Set modeler JSON

Fluxo automático sem ações, decisões ou variáveis definidas. Não possui pontos de entrada, atualizações ou criações de registros, nem lógica implementada.  
Resultado principal: fluxo vazio intitulado "DW NPX | Set modeler JSON" sem funcionalidade operacional.

| Tipo de acionador | Tipo de registro |
| ----------------- | ---------------- |
| RecordBeforeSave  | Create           |

### DW - Opp Line Item - Before Flow (Marcar como serviço)

DW - Opp Line Item - Before Flow (Marcar como serviço) {!$Flow.CurrentDateTime}

| Tipo de acionador | Tipo de registro |
| ----------------- | ---------------- |
| RecordBeforeSave  | Create           |

### DW - Produto da opp - Produto da opp vira item de linha da OT

DW - Ordem de trabalho - Produto da opp vira item de linha da OT {!$Flow.CurrentDateTime}

| Tipo de acionador | Tipo de registro |
| ----------------- | ---------------- |
| RecordAfterSave   | Create           |

### DW - Produto de oportunidade - Atribuir ordem de trabalho de oportunidade

DW - Produto de oportunidade - Atribuir ordem de trabalho de oportunidade {!$Flow.CurrentDateTime}

| Tipo de acionador | Tipo de registro |
| ----------------- | ---------------- |
| RecordAfterSave   | Create           |

### DW - Produto de oportunidade - Atribuir tipo do item

DW - Produto de oportunidade - Atribuir tipo do item {!$Flow.CurrentDateTime}

| Tipo de acionador | Tipo de registro |
| ----------------- | ---------------- |
| RecordAfterSave   | Create           |

### DW - Produto de oportunidade - Calcular desconto ao alterar preço de venda

DW - Produto de oportunidade - Calcular desconto ao alterar preço de venda {!$Flow.CurrentDateTime}

| Tipo de acionador | Tipo de registro |
| ----------------- | ---------------- |
| RecordBeforeSave  | CreateAndUpdate  |

### DW - Produto de oportunidade - Calcular preço de venda ao alterar preço sugerido

DW - Produto de oportunidade - Calcular preço de venda ao alterar preço sugerido {!$Flow.CurrentDateTime}

| Tipo de acionador | Tipo de registro |
| ----------------- | ---------------- |
| RecordBeforeSave  | Update           |

### DW - Produto de oportunidade - Copiar quantidade alocada

DW - Produto de oportunidade - Copiar quantidade alocada {!$Flow.CurrentDateTime}

| Tipo de acionador | Tipo de registro |
| ----------------- | ---------------- |
| RecordBeforeSave  | Update           |

### DW - Produto de oportunidade - Criar item da ordem de trabalho peça

DW - Produto de oportunidade - Criar item da ordem de trabalho {!$Flow.CurrentDateTime}

| Tipo de acionador | Tipo de registro |
| ----------------- | ---------------- |
| RecordAfterSave   | Update           |

### DW - Produto de oportunidade - Criar item da ordem de trabalho serviço

DW - Produto de oportunidade - Criar item da ordem de trabalho peça {!$Flow.CurrentDateTime}

| Tipo de acionador | Tipo de registro |
| ----------------- | ---------------- |
| RecordAfterSave   | CreateAndUpdate  |

### DW - Produto de oportunidade - Deixar integração de impostos em andamento

DW - Produto de oportunidade - Deixar integração de impostos em andamento {!$Flow.CurrentDateTime}

| Tipo de acionador | Tipo de registro |
| ----------------- | ---------------- |
| RecordBeforeSave  | Create           |

### DW - Produto de oportunidade - Espelhar item de trabalho

DW - Produto de oportunidade - Espelhar item de trabalho {!$Flow.CurrentDateTime}

| Tipo de acionador | Tipo de registro |
| ----------------- | ---------------- |
| RecordAfterSave   | CreateAndUpdate  |

### DW - Produto de oportunidade - Espelhar campos de fatores para impostos

DW - Produto de oportunidade - Espelhar campos de impostos {!$Flow.CurrentDateTime}

| Tipo de acionador | Tipo de registro |
| ----------------- | ---------------- |
| RecordBeforeSave  | CreateAndUpdate  |

### DW - Produto de oportunidade - Excluir itens relacionados

DW - Produto de oportunidade - Excluir itens relacionados {!$Flow.CurrentDateTime}

| Tipo de acionador  | Tipo de registro |
| ------------------ | ---------------- |
| RecordBeforeDelete | Delete           |

### DW - Produto de oportunidade - Excluir reservas

DW - Produto de oportunidade - Excluir reservas {!$Flow.CurrentDateTime}

| Tipo de acionador  | Tipo de registro |
| ------------------ | ---------------- |
| RecordBeforeDelete | Delete           |

### DW - Produto de oportunidade - Fechar oportunidade se tudo alocado

DW - Produto de oportunidade - Fechar oportunidade se tudo alocado {!$Flow.CurrentDateTime}

| Tipo de acionador | Tipo de registro |
| ----------------- | ---------------- |
| RecordAfterSave   | Update           |

### DW - Produto de oportunidade - Marca oportunidade como integrando

DW - Produto de oportunidade - Marca oportunidade como integrando {!$Flow.CurrentDateTime}

| Tipo de acionador | Tipo de registro |
| ----------------- | ---------------- |
| RecordAfterSave   | CreateAndUpdate  |

### DW - Produto de oportunidade - Negativar item da ordem de trabalho

DW - Produto de oportunidade - Negativar item da ordem de trabalho {!$Flow.CurrentDateTime}

| Tipo de acionador  | Tipo de registro |
| ------------------ | ---------------- |
| RecordBeforeDelete | Delete           |

### DW - Produto de oportunidade - Reserva automática

DW - Produto de oportunidade - Reserva automática {!$Flow.CurrentDateTime}

| Tipo de acionador | Tipo de registro |
| ----------------- | ---------------- |
| RecordAfterSave   | CreateAndUpdate  |

### DW - Produto de oportunidade - Reserva automática draft

DW - Produto de oportunidade - Reserva automática draft {!$Flow.CurrentDateTime}

| Tipo de acionador | Tipo de registro |
| ----------------- | ---------------- |
| RecordAfterSave   | CreateAndUpdate  |

### DW - Produto da opp - Exclusão - Exclui tbm na OT

DW - Produto da opp - Exclusão - Exclui tbm na OT {!$Flow.CurrentDateTime}

| Tipo de acionador  | Tipo de registro |
| ------------------ | ---------------- |
| RecordBeforeDelete | Delete           |

### DW - Recálculo de preço de venda

DW - Recálculo de preço de venda {!$Flow.CurrentDateTime}

| Tipo de acionador | Tipo de registro |
| ----------------- | ---------------- |
| RecordAfterSave   | CreateAndUpdate  |

### DW - propaga desvio de markup para campo auxiliar

DW - propaga desvio de markup para campo auxiliar {!$Flow.CurrentDateTime}

| Tipo de acionador | Tipo de registro |
| ----------------- | ---------------- |
| RecordAfterSave   | Update           |

## Ações Rápidas

| Rótulo                    | Nome de API                 |
| ------------------------- | --------------------------- |
| Reservar compromisso      | FSL__Book_Appointment       |
| Candidatos                | FSL__Candidates             |
| Caso de devolução         | Caso_de_devolucao           |
| Contato                   | Contato                     |
| Criar Caso - Serviço      | CriarCasoServico            |
| Cliente                   | DWCliente                   |
| Compromisso               | DWCompromisso               |
| Vender Peça(s)            | DWVenderPeca                |
| Emergência                | FSL__Emergency              |
| Iniciar atendimento       | InciarAtendimento           |
| Nova conta                | NewAccount                  |
| Novo contato              | NewContact                  |
| Novo compromisso          | FSL__NewEvent               |
| Novo compromisso          | NewEvent                    |
| Novo grupo                | NewGroup                    |
| Nova oportunidade         | NewOpportunity              |
| Novo caso                 | NovoCasoServicos            |
| Novo caso - Serviços      | Novo_caso_servicos          |
| Email                     | SendEmail                   |
| Ações inteligentes móveis | FeedItem.MobileSmartActions |

## Acionadores Apex

### ProductDependencyTrigger

Status: Active

| Uso                 | Ativo |
| ------------------- | ----- |
| Antes de Inserir    | Não   |
| Depois de Inserir   | Sim   |
| Antes de Atualizar  | Não   |
| Depois de Atualizar | Não   |
| Antes de Excluir    | Sim   |
| Depois de Excluir   | Não   |
| Depois de Recuperar | Não   |

### OpportunityLineItemTrigger

Status: Active

| Uso                 | Ativo |
| ------------------- | ----- |
| Antes de Inserir    | Não   |
| Depois de Inserir   | Sim   |
| Antes de Atualizar  | Não   |
| Depois de Atualizar | Sim   |
| Antes de Excluir    | Não   |
| Depois de Excluir   | Não   |
| Depois de Recuperar | Não   |

# Dashboards

## Sales and Marketing Dashboards

| Nome                    | Nome de API                    | Descrição                      |
| ----------------------- | ------------------------------ | ------------------------------ |
| Marketing Dashboard     | Best_Practice_Leads_Dashboard  | -                              |
| Adoption Dashboard      | AdoptionDashboard              | -                              |
| Sales Manager Dashboard | Best_Practices_Dashboard6      | Best Practices Sales Dashboard |
| Análise de margem       | LzeLrsKlSHqfofEyrXxahHDPYyAPiS | -                              |

## Activities

| Nome                 | Nome de API         | Descrição |
| -------------------- | ------------------- | --------- |
| Activities Dashboard | NonA360EacDashboard | -         |

## Preconfigured Sales Cloud Dashboards

| Nome                                | Nome de API                   | Descrição                                                                                         |
| ----------------------------------- | ----------------------------- | ------------------------------------------------------------------------------------------------- |
| Sales Manager: Key Metrics          | Best_Practices_Dashboard61111 | Track your team’s performance and progress toward revenue goals.                                  |
| Painel básico de vendas (Daspe Web) | Best_Practices_Dashboard61211 | Track how individual reps are making progress toward revenue goals and what deals need attention. |
| Key Performance Indicators          | Best_Practices_Dashboard6131  | Track revenue, opportunity trends, and pipeline impact against your company goals.                |
| Executive Sponsor: Key Metrics      | Best_Practices_Dashboard6132  | Track FYTD revenue, opportunity trends, and top accounts.                                         |

## Sales Engagement Sample Dashboards

| Nome                              | Nome de API                     | Descrição                                                                          |
| --------------------------------- | ------------------------------- | ---------------------------------------------------------------------------------- |
| Sales Engagement Sample Dashboard | CRM_180925_HVS_Sample_Dashboard | See how well your cadences, sales reps, email templates, and call scripts perform. |

## Service Dashboards

| Nome                       | Nome de API               | Descrição |
| -------------------------- | ------------------------- | --------- |
| Agent Supervisor Overview  | Agent_Supervisor_Overview | -         |
| Service Executive Overview | Service_Exec_Overview     | -         |
| Service KPIs               | Service_KPIs              | -         |

## Field Service Copilot Dashboards

| Nome                                  | Nome de API                      | Descrição |
| ------------------------------------- | -------------------------------- | --------- |
| Copilot: Summary of Scheduling Issues | CopilotSummaryOfSchedulingIssues | -         |

## Field Service Work Capacity Dashboards

| Nome                                                              | Nome de API                              | Descrição                                                                                                                                                        |
| ----------------------------------------------------------------- | ---------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Analyze Availability of Workforce.V2                              | FieldServiceWorkCapacityDashboards       | The following dashboard will accommodate Field Service Work Capacity dashboards to guide and assist the planner                                                  |
| Aggregated Workstreams Utilization                                | RRYSGLHrmcRLDBGKUxngyrueoGIwXW1          | Compare the total daily consumption to the daily configured work capacity limit or daily availability to follow trends in consumption over the time horizon.     |
| Weekly Usage of Workstreams Compared to Limit and Availability    | vwfpkAEnvconLBZYbbJkPTWzLlVfrb           | Understand the supply and demand distribution by comparing the weekly consumption to the configured limits and availability by service territory and workstream. |
| Compare Aggregated Workstream Utilization V2                      | CompareAggregatedWorkstreamUtilizationV2 | Compare the total daily consumption to the daily configured work capacity limit or daily availability to follow trends in consumption over the time horizon.     |
| Weekly Usage of Workstreams Compared to Limit and Availability V2 | WeeklyAggregatedWorkstreamUtilizationV2  | Understand the supply and demand distribution by comparing the weekly consumption to the configured limits and availability by service territory and workstream. |

## Gerenciamento de contas - Daspe Web

| Nome                         | Nome de API                     | Descrição |
| ---------------------------- | ------------------------------- | --------- |
| AC - Gerenciamento de contas | CVNToFhWrLERAjAOoFTrFEobZJjydu1 | -         |

## Trailhead

| Nome                       | Nome de API                | Descrição |
| -------------------------- | -------------------------- | --------- |
| Trailhead Overview         | Trailhead_Overview         | -         |
| Trailhead for Sales Team   | Trailhead_for_Sales_Org    | -         |
| Trailhead for Service Team | Trailhead_for_Service_Team | -         |
| Trailmix Overview          | Trailmix_Overview          | -         |

## Pública

| Nome          | Nome de API                    | Descrição |
| ------------- | ------------------------------ | --------- |
| Field Service | ovbihSmKZKUJkIPqnzBsuosUoqlYnw | -         |

## Painéis privados

| Nome  | Nome de API                    | Descrição |
| ----- | ------------------------------ | --------- |
| Conta | vNjwrzPkFgQEPXTSrysGcUQXofNUwe | -         |

## Setup do NPX

| Nome         | Nome de API                    | Descrição |
| ------------ | ------------------------------ | --------- |
| Setup do NPX | tzpICjhZtxrbOMyUGLtgmijBRiUjIo | -         |

# Conjuntos de Valores Globais

Nenhum conjunto de valores global encontrado.

# Lightning Web Components

| Nome                                            | Namespace | Nome de API                              | Descrição                                                                                                             |
| ----------------------------------------------- | --------- | ---------------------------------------- | --------------------------------------------------------------------------------------------------------------------- |
| DW | Proposta Customizada PDF                   | -         | dwCustomProposal                         | -                                                                                                                     |
| dwDocumentValidation                            | -         | dwDocumentValidation                     | -                                                                                                                     |
| DW NOX | Mercadão                               | -         | noxMercadao                              | -                                                                                                                     |
| DW NOX | TETA                                   | DW_NOX    | dwnoxcontainer                           | -                                                                                                                     |
| richtextField                                   | DW_NOX    | richtextField                            | -                                                                                                                     |
| DW | Liberar solicitações de peças              | -         | dwUnlockBookingController                | -                                                                                                                     |
| DW | Opportunity Global Discount                | -         | dwOpportunityGlobalDiscount              | -                                                                                                                     |
| DW - Condições de Pagamento                     | -         | dwOpportunityPaymentCondition            | -                                                                                                                     |
| dwOpportunityPaymentConditionModal              | -         | dwOpportunityPaymentConditionModal       | -                                                                                                                     |
| dwOpportunityPaymentConditionRow                | -         | dwOpportunityPaymentConditionRow         | -                                                                                                                     |
| DW | Visualizar estrutura de catálogo de preços | DW_NPX    | pricebookTreeView                        | -                                                                                                                     |
| actionLaucher                                   | DW_NOX    | actionLaucher                            | -                                                                                                                     |
| actionsSetup                                    | DW_NOX    | actionsSetup                             | -                                                                                                                     |
| dwConsistencyField                              | DW_NOX    | dwConsistencyField                       | -                                                                                                                     |
| dwCustomCheckboxField                           | DW_NOX    | dwCustomCheckboxField                    | -                                                                                                                     |
| dwFlagIndicatorField                            | DW_NOX    | dwFlagIndicatorField                     | -                                                                                                                     |
| dwGraphField                                    | DW_NOX    | dwGraphField                             | -                                                                                                                     |
| Campo para tabela de dados hoverable            | DW_NOX    | dwHoverableDatatableField                | -                                                                                                                     |
| dwLWCHelper                                     | DW_NOX    | dwLWCHelper                              | -                                                                                                                     |
| DW | LWC Helper | V3                            | DW_NOX    | dwLwcHelperV3                            | Usar como extensão do componente principal. Métodos de helper e do Lightning estão inclusos.                          |
| dwModalProductsTable                            | DW_NOX    | dwModalProductsTable                     | -                                                                                                                     |
| dwPicklistField                                 | DW_NOX    | dwPicklistField                          | -                                                                                                                     |
| dwPicklistMultiField                            | DW_NOX    | dwPicklistMultiField                     | -                                                                                                                     |
| dwProgressField                                 | DW_NOX    | dwProgressField                          | -                                                                                                                     |
| dwProvider                                      | DW_NOX    | dwProvider                               | -                                                                                                                     |
| dwQueryBuilderConditionItem                     | DW_NOX    | dwQueryBuilderConditionItem              | -                                                                                                                     |
| DW | Query builder                              | DW_NOX    | dwQueryBuilderRoot                       | -                                                                                                                     |
| dwQueryFieldSelector                            | DW_NOX    | dwQueryFieldSelector                     | -                                                                                                                     |
| dwRangeIndicatorField                           | DW_NOX    | dwRangeIndicatorField                    | -                                                                                                                     |
| dwSearchLookupField                             | DW_NOX    | dwSearchLookupField                      | -                                                                                                                     |
| dwSearchLookupFieldEdit                         | DW_NOX    | dwSearchLookupFieldEdit                  | -                                                                                                                     |
| dwSearchLookupFieldStatic                       | DW_NOX    | dwSearchLookupFieldStatic                | -                                                                                                                     |
| dwVersliteDatatable                             | DW_NOX    | dwVersliteDatatable                      | -                                                                                                                     |
| dwVersliteTreegrid                              | DW_NOX    | dwVersliteTreegrid                       | -                                                                                                                     |
| dynamicField                                    | DW_NOX    | dynamicField                             | -                                                                                                                     |
| fieldsSelector                                  | DW_NOX    | fieldsSelector                           | -                                                                                                                     |
| filterBuilder                                   | DW_NOX    | filterBuilder                            | -                                                                                                                     |
| generalSetup                                    | DW_NOX    | generalSetup                             | -                                                                                                                     |
| helper                                          | DW_NOX    | helper                                   | -                                                                                                                     |
| imagemView                                      | DW_NOX    | imagemView                               | -                                                                                                                     |
| lineItemForm                                    | DW_NOX    | lineItemForm                             | -                                                                                                                     |
| metaProvider                                    | DW_NOX    | metaProvider                             | -                                                                                                                     |
| modalBooking                                    | DW_NOX    | modalBooking                             | -                                                                                                                     |
| modalPriceHistory                               | DW_NOX    | modalPriceHistory                        | -                                                                                                                     |
| modalProductsTable                              | DW_NOX    | modalProductsTable                       | -                                                                                                                     |
| modalSearchLookupField                          | DW_NOX    | modalSearchLookupField                   | -                                                                                                                     |
| modalStockDetails                               | DW_NOX    | modalStockDetails                        | -                                                                                                                     |
| oliChangeListener                               | DW_NOX    | oliChangeListener                        | -                                                                                                                     |
| priceHistoryFieldSelector                       | DW_NOX    | priceHistoryFieldSelector                | -                                                                                                                     |
| DW NOX | Tabela de produtos                     | DW_NOX    | productsTable                            | -                                                                                                                     |
| productsTableFilter                             | DW_NOX    | productsTableFilter                      | -                                                                                                                     |
| Guia de configuração do NOX                     | DW_NOX    | setup                                    | As configurações do NOX incluem como a possibilidade de venda será calculada, de onde o estoque será obtido, etc.     |
| setupService                                    | DW_NOX    | setupService                             | -                                                                                                                     |
| sharing                                         | DW_NOX    | sharing                                  | -                                                                                                                     |
| sortOpportunityItems                            | DW_NOX    | sortOpportunityItems                     | -                                                                                                                     |
| DW NOX | Visualizador de estoque e reserva      | DW_NOX    | stockDetails                             | -                                                                                                                     |
| stockSetup                                      | DW_NOX    | stockSetup                               | -                                                                                                                     |
| DW NOX | Linha do tempo                         | DW_NOX    | timeline                                 | Este componente deve ser inserido apenas em telas de oportunidade, pedido e cotação.                                  |
| timelineSObjectSetup                            | DW_NOX    | timelineSObjectSetup                     | -                                                                                                                     |
| timelineSetup                                   | DW_NOX    | timelineSetup                            | -                                                                                                                     |
| uploadFile                                      | DW_NOX    | uploadFile                               | -                                                                                                                     |
| utils                                           | DW_NOX    | utils                                    | -                                                                                                                     |
| DW | LWC Helper | V3                            | DW_AC     | dwLwcHelperV3                            | Usar como extensão do componente principal. Métodos de helper e do Lightning estão inclusos.                          |
| LWC Helper                                      | DW_AC     | helper                                   | Usar como extensão do componente principal.                                                                           |
| Caixa de destaque do AC                         | DW_AC     | recordHighlightsBox                      | -                                                                                                                     |
| DW AC | Configurador                            | DW_AC     | setup                                    | -                                                                                                                     |
| Split Opportunity Lwc                           | DW_SPT    | splitOpportunityLWC                      | Split Opportunity Lwc                                                                                                 |
| Record Map Inner                                | ltngMap   | recordMap                                | Lightning Component that shows an address on a map, given the correct address parameters within Lightning App Builder |
| Record Map                                      | ltngMap   | recordMapWrap                            | Lightning Component that shows an address on a map, given the correct address parameters within Lightning App Builder |
| animation                                       | FSL       | animation                                | -                                                                                                                     |
| baseAttribute                                   | FSL       | baseAttribute                            | -                                                                                                                     |
| baseAxis                                        | FSL       | baseAxis                                 | -                                                                                                                     |
| Capacity Limit Edit Form                        | FSL       | capacityLimitEditForm                    | Capacity Limit Edit Form                                                                                              |
| Capacity Limit Summary Conf                     | FSL       | capacityLimitSummaryConf                 | Capacity Limit Summary Conf                                                                                           |
| capacityLimitSummaryDateCmp                     | FSL       | capacityLimitSummaryDateCmp              | -                                                                                                                     |
| capacityLimitSummaryMultiSelectComboBox         | FSL       | capacityLimitSummaryMultiSelectComboBox  | -                                                                                                                     |
| capacityLimitSummaryScopeCmp                    | FSL       | capacityLimitSummaryScopeCmp             | -                                                                                                                     |
| Capacity Limit Summary Sort                     | FSL       | capacityLimitSummarySort                 | Capacity Limit Summary Sort                                                                                           |
| Capacity Limit Summary Usage Card               | FSL       | capacityLimitSummaryUsageCard            | Capacity Limit Summary Usage Card                                                                                     |
| Capacity Limit Summary View                     | FSL       | capacityLimitSummaryView                 | -                                                                                                                     |
| carouselComponent                               | FSL       | carouselComponent                        | -                                                                                                                     |
| cartesianAxis                                   | FSL       | cartesianAxis                            | -                                                                                                                     |
| cartesianLinearAxis                             | FSL       | cartesianLinearAxis                      | -                                                                                                                     |
| chart                                           | FSL       | chart                                    | -                                                                                                                     |
| chartConfigService                              | FSL       | chartConfigService                       | -                                                                                                                     |
| constants                                       | FSL       | constants                                | -                                                                                                                     |
| countRule                                       | FSL       | countRule                                | -                                                                                                                     |
| cssLibrary                                      | FSL       | cssLibrary                               | -                                                                                                                     |
| data                                            | FSL       | data                                     | -                                                                                                                     |
| dataset                                         | FSL       | dataset                                  | -                                                                                                                     |
| LogsTable                                       | FSL       | generatedLogsTable                       | LogsTable                                                                                                             |
| Integrity Checker Async Results Datatable       | FSL       | integrityCheckerAsyncResultsDatatable    | Integrity Checker Async Results Datatable                                                                             |
| Integrity Checker Hbv Inputs                    | FSL       | integrityCheckerHbvInputs                | Integrity Checker Hbv Inputs                                                                                          |
| Integrity Checker Hbv Inputs Modal              | FSL       | integrityCheckerHbvInputsModal           | Integrity Checker Hbv Inputs Modal                                                                                    |
| Integrity Checker Hbv Page                      | FSL       | integrityCheckerHbvPage                  | Integrity Checker Hbv Page                                                                                            |
| Integrity Checker Hbv Ribbon                    | FSL       | integrityCheckerHbvRibbon                | Integrity Checker Hbv Ribbon                                                                                          |
| Integrity Checker Health Checks Page            | FSL       | integrityCheckerHealthChecksPage         | Main health checks page                                                                                               |
| Integrity Checker Health Checks Results Out     | FSL       | integrityCheckerHealthChecksResultsOut   | Integrity Checker Health Checks Results Out                                                                           |
| Integrity Checker More Info Page                | FSL       | integrityCheckerMoreInfoPage             | Integrity Checker More Info Page                                                                                      |
| Integrity Checker Results Datatable             | FSL       | integrityCheckerResultsDatatable         | Integrity Checker Results Datatable                                                                                   |
| Integrity Checker Timephased Page               | FSL       | integrityCheckerTimePhasedPage           | Integrity Checker Timephased Page                                                                                     |
| Integrity Checker Visual Picker                 | FSL       | integrityCheckerVisualPicker             | Integrity Checker Visual Picker                                                                                       |
| legend                                          | FSL       | legend                                   | -                                                                                                                     |
| Lightning Datetime Picker                       | FSL       | lightningDatetimePicker                  | Lightning Datetime Picker                                                                                             |
| lightningModal                                  | FSL       | lightningModal                           | -                                                                                                                     |
| messageStateComponent                           | FSL       | messageStateComponent                    | -                                                                                                                     |
| Multi Percentage Progress Bar                   | FSL       | multiPercentageProgressBar               | Multi Percentage Progress Bar                                                                                         |
| nanoid                                          | FSL       | nanoid                                   | -                                                                                                                     |
| objectiveBarGraph                               | FSL       | objectiveBarGraph                        | -                                                                                                                     |
| optCenterActivityLogTab                         | FSL       | optCenterActivityLogTab                  | -                                                                                                                     |
| Opt Center Request Jsons By Ids Sub Tab         | FSL       | optCenterRequestJsonsByIdsSubTab         | Opt Center Request Jsons By Ids Sub Tab                                                                               |
| optCenterRequestJsonsTab                        | FSL       | optCenterRequestJsonsTab                 | -                                                                                                                     |
| optHubBarChart                                  | FSL       | optHubBarChart                           | -                                                                                                                     |
| optHubBarComplexChart                           | FSL       | optHubBarComplexChart                    | -                                                                                                                     |
| optHubDataList                                  | FSL       | optHubDataList                           | -                                                                                                                     |
| optHubFilter                                    | FSL       | optHubFilter                             | -                                                                                                                     |
| optHubHomeTab                                   | FSL       | optHubHomeTab                            | -                                                                                                                     |
| optHubMetricBoxTitle                            | FSL       | optHubMetricBoxTitle                     | -                                                                                                                     |
| optHubPolarAreaChart                            | FSL       | optHubPolarAreaChart                     | -                                                                                                                     |
| optHubPolicyTab                                 | FSL       | optHubPolicyTab                          | -                                                                                                                     |
| optHubProgressbar                               | FSL       | optHubProgressbar                        | -                                                                                                                     |
| optHubProgressbarItem                           | FSL       | optHubProgressbarItem                    | -                                                                                                                     |
| optHubResourceTab                               | FSL       | optHubResourceTab                        | -                                                                                                                     |
| optHubScheduleTab                               | FSL       | optHubScheduleTab                        | -                                                                                                                     |
| optHubStackBarChart                             | FSL       | optHubStackBarChart                      | -                                                                                                                     |
| optHubTableRowTemplate                          | FSL       | optHubTableRowTemplate                   | -                                                                                                                     |
| optHubTableViewTemplate                         | FSL       | optHubTableViewTemplate                  | -                                                                                                                     |
| optHubTooltipTemplate                           | FSL       | optHubTooltipTemplate                    | -                                                                                                                     |
| Optimization Insights Health Check              | FSL       | optInsightHealthCheck                    | -                                                                                                                     |
| optInsightHealthCheckShowMore                   | FSL       | optInsightHealthCheckShowMore            | -                                                                                                                     |
| optInsightHealthCheckTable                      | FSL       | optInsightHealthCheckTable               | -                                                                                                                     |
| optInsightHealthCheckTest                       | FSL       | optInsightHealthCheckTest                | -                                                                                                                     |
| Optimization Center                             | FSL       | optimizationCenter                       | Optimization Center                                                                                                   |
| Optimization Hub                                | FSL       | optimizationHub                          | Beta                                                                                                                  |
| optimizationInsightCapacityGraph                | FSL       | optimizationInsightCapacityGraph         | -                                                                                                                     |
| optimizationInsightKpiResultColumn              | FSL       | optimizationInsightKpiResultColumn       | -                                                                                                                     |
| optimizationInsightMessage                      | FSL       | optimizationInsightMessage               | -                                                                                                                     |
| optimizationInsightNotCompleted                 | FSL       | optimizationInsightNotCompleted          | -                                                                                                                     |
| Optimization Insights KPIs                      | FSL       | optimizationInsightsKPIs                 | -                                                                                                                     |
| Optimization Insights Metrics                   | FSL       | optimizationInsightsMetrics              | -                                                                                                                     |
| Optimization Insights Summary                   | FSL       | optimizationInsightsSummary              | -                                                                                                                     |
| radialAxis                                      | FSL       | radialAxis                               | -                                                                                                                     |
| radialLinearAxis                                | FSL       | radialLinearAxis                         | -                                                                                                                     |
| reactivityManager                               | FSL       | reactivityManager                        | -                                                                                                                     |
| schedulingAssistantSlotsTable                   | FSL       | schedulingAssistantSlotsTable            | -                                                                                                                     |
| schedulingAssistantSlotsTableRow                | FSL       | schedulingAssistantSlotsTableRow         | -                                                                                                                     |
| schedulingAssistantSlotsTableRowColor           | FSL       | schedulingAssistantSlotsTableRowColor    | -                                                                                                                     |
| schedulingAssistantSlotsTableTooltip            | FSL       | schedulingAssistantSlotsTableTooltip     | -                                                                                                                     |
| schedulingAssistantStencil                      | FSL       | schedulingAssistantStencil               | -                                                                                                                     |
| Appointment Insights                            | FSL       | schedulingAssistantTab                   | Beta                                                                                                                  |
| schedulingAssistantWorkRuleItem                 | FSL       | schedulingAssistantWorkRuleItem          | -                                                                                                                     |
| schedulingAssistantWorkRules                    | FSL       | schedulingAssistantWorkRules             | -                                                                                                                     |
| Searchable Dual Picklist                        | FSL       | searchableDualPicklist                   | Searchable Dual Picklist                                                                                              |
| title                                           | FSL       | title                                    | -                                                                                                                     |
| tooltip                                         | FSL       | tooltip                                  | -                                                                                                                     |
| utils                                           | FSL       | utils                                    | -                                                                                                                     |
| DW | Clonar oportunidade                        | -         | cloneOpportunity                         | -                                                                                                                     |
| DW | Inicializador de dados                     | -         | dataBoot                                 | -                                                                                                                     |
| Consultar dados API do Sintegra                 | -         | dwConsultaSintegra                       | -                                                                                                                     |
| DW | LWC helper                                 | -         | dwLwcHelper                              | -                                                                                                                     |
| dwSintegraHelper                                | -         | dwSintegraHelper                         | -                                                                                                                     |
| Caixa de destaque 1.0                           | -         | dw_record_highlights_box                 | -                                                                                                                     |
| helper                                          | -         | helper                                   | -                                                                                                                     |
| agGridList                                      | FSL       | agGridList                               | -                                                                                                                     |
| dhtmlxChart                                     | FSL       | dhtmlxChart                              | -                                                                                                                     |
| Dispatch Console                                | FSL       | dispatchConsole                          | Dispatch Console                                                                                                      |
| dispatchConsoleCSSLibrary                       | FSL       | dispatchConsoleCSSLibrary                | -                                                                                                                     |
| dispatchConsoleChart                            | FSL       | dispatchConsoleChart                     | -                                                                                                                     |
| dispatchConsoleChartDataProcessor               | FSL       | dispatchConsoleChartDataProcessor        | -                                                                                                                     |
| dispatchConsoleChartLoadingStencil              | FSL       | dispatchConsoleChartLoadingStencil       | -                                                                                                                     |
| dispatchConsoleChartUtils                       | FSL       | dispatchConsoleChartUtils                | -                                                                                                                     |
| dispatchConsoleHeader                           | FSL       | dispatchConsoleHeader                    | -                                                                                                                     |
| dispatchConsoleListDataDisplay                  | FSL       | dispatchConsoleListDataDisplay           | -                                                                                                                     |
| dispatchConsoleMetadataProcessor                | FSL       | dispatchConsoleMetadataProcessor         | -                                                                                                                     |
| dispatchConsoleServiceList                      | FSL       | dispatchConsoleServiceList               | -                                                                                                                     |
| dispatchConsoleTerritoriesTree                  | FSL       | dispatchConsoleTerritoriesTree           | -                                                                                                                     |
| DW | LWC Helper | V3                            | -         | dwLwcHelperV3                            | Usar como extensão do componente principal. Métodos de helper e do Lightning estão inclusos.                          |
| Emissor de proposta                             | -         | dwProposalEmitter                        | -                                                                                                                     |
| dispatchConsoleAbsenceForm                      | FSL       | dispatchConsoleAbsenceForm               | -                                                                                                                     |
| dispatchConsoleActions                          | FSL       | dispatchConsoleActions                   | -                                                                                                                     |
| dispatchConsoleActionsUtils                     | FSL       | dispatchConsoleActionsUtils              | -                                                                                                                     |
| dispatchConsoleLayoutForm                       | FSL       | dispatchConsoleLayoutForm                | -                                                                                                                     |
| dispatchConsoleListUtils                        | FSL       | dispatchConsoleListUtils                 | -                                                                                                                     |
| dispatchConsolePopover                          | FSL       | dispatchConsolePopover                   | -                                                                                                                     |
| dispatchConsolePopoverFields                    | FSL       | dispatchConsolePopoverFields             | -                                                                                                                     |
| dispatchConsolePushService                      | FSL       | dispatchConsolePushService               | -                                                                                                                     |
| dispatchConsoleServiceListLoadingStencil        | FSL       | dispatchConsoleServiceListLoadingStencil | -                                                                                                                     |
| dispatchConsoleSidePanel                        | FSL       | dispatchConsoleSidePanel                 | -                                                                                                                     |
| focusTrap                                       | FSL       | focusTrap                                | -                                                                                                                     |
| productsTableFooter                             | DW_NOX    | productsTableFooter                      | -                                                                                                                     |
| summaryFieldsSetup                              | DW_NOX    | summaryFieldsSetup                       | -                                                                                                                     |
| summaryFieldsSetupItem                          | DW_NOX    | summaryFieldsSetupItem                   | -                                                                                                                     |
| adminSetup                                      | DW_NPX    | adminSetup                               | -                                                                                                                     |
| DW | LWC Helper | V3                            | DW_NPX    | dwLwcHelperV3                            | Usar como extensão do componente principal. Métodos de helper e do Lightning estão inclusos.                          |
| dwNpxEnvManager                                 | DW_NPX    | dwNpxEnvManager                          | -                                                                                                                     |
| DW NPX | Navegar para o modo de edição          | DW_NPX    | dwNpxNavigator                           | -                                                                                                                     |
| DW | NPX | Visualizar modelagem de preço        | DW_NPX    | dwNpxPriceModelerView                    | -                                                                                                                     |
| dwNpxPricebookQualifier                         | DW_NPX    | dwNpxPricebookQualifier                  | -                                                                                                                     |
| DW | NPX | Indicador de processo do catálogo    | DW_NPX    | dwNpxProcessIndicator                    | -                                                                                                                     |
| dwNpxProductQualifier                           | DW_NPX    | dwNpxProductQualifier                    | -                                                                                                                     |
| DW NPX | Raiz do qualificador                   | DW_NPX    | dwNpxQualifierRoot                       | -                                                                                                                     |
| dwProvider                                      | DW_NPX    | dwProvider                               | -                                                                                                                     |
| dwQueryBuilderConditionItem                     | DW_NPX    | dwQueryBuilderConditionItem              | -                                                                                                                     |
| DW | Query builder                              | DW_NPX    | dwQueryBuilderRoot                       | -                                                                                                                     |
| dwQueryFieldSelector                            | DW_NPX    | dwQueryFieldSelector                     | -                                                                                                                     |
| dwQueryProvider                                 | DW_NPX    | dwQueryProvider                          | -                                                                                                                     |
| helper                                          | DW_NPX    | helper                                   | -                                                                                                                     |
| DW NPX | Gerenciar qualificadores de herança    | DW_NPX    | inheritanceQualifiers                    | Define a possibilidade de criar qualificadores horizontais para todos os filhos                                       |
| DW NPX | Ouvinte do NPX                         | DW_NPX    | listenerNpx                              | Ouvinte de processos do NPX. Ex.: Cálculo horizontal.                                                                 |
| Gerenciador de perfil de qualificação           | DW_NPX    | manageQualifierProfile                   | -                                                                                                                     |
| manageQualifierProfileModal                     | DW_NPX    | manageQualifierProfileModal              | -                                                                                                                     |
| metaProvider                                    | DW_NPX    | metaProvider                             | -                                                                                                                     |
| picklistValueSetter                             | DW_NPX    | picklistValueSetter                      | -                                                                                                                     |
| Seletor de perfil de qualificação no fator      | DW_NPX    | profileFactorContainer                   | -                                                                                                                     |
| Gerenciador de qualificador                     | DW_NPX    | qualifierManager                         | -                                                                                                                     |
| selectQualifierProfile                          | DW_NPX    | selectQualifierProfile                   | -                                                                                                                     |
| setupProvider                                   | DW_NPX    | setupProvider                            | -                                                                                                                     |

# Classes Apex

| Nome                                     | Versão da API | Status | Resumo IA                                                                                                                                                                                                                                                           |
| ---------------------------------------- | ------------- | ------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DWGetFichaSEGIntegrable                  | 64            | Active | Executa uma chamada GET ao endpoint ERP para buscar dados do veículo pelo chassi, processa a resposta JSON e disponibiliza informações detalhadas para automatizar consultas e melhorar decisões.                                                                   |
| DW_GetFichaSegIntegrableTemplate         | 64            | Active | Define um template de dados veiculares para integrar fichas de seguro, armazenando informações chave como cliente, modelo, chassi e datas, facilitando processos automatizados de seguro e vendas.                                                                  |
| DwGetAtivosFichaIntegrableBatch          | 64            | Active | Executa integração batch e agendada para atualizar registros Asset com dados externos via chamada HTTP, sincronizando informações de veículos e vinculando contas automaticamente.                                                                                  |
| DwGetAtivosFichaIntegrableBatchTest      | 64            | Active | Testa a classe batch que integra dados de ativos via API, simulando chamadas HTTP e criando dados de contas e ativos para validar agendamento, execução síncrona e cancelamento do processo.                                                                        |
| MockApiGetFicha                          | 64            | Active | Simula uma resposta HTTP com dados JSON fixos para testes de integração, garantindo que chamadas externas retornem informações consistentes sem impactar dados reais.                                                                                               |
| DwOpportunityIntegrableBatchTest         | 64            | Active | Testa a integração batch de Oportunidades, simulando dados e chamadas HTTP para validar processos automatizados de sincronização, agendamento e cancelamento, garantindo dados consistentes.                                                                        |
| MockApiGetSimulacao                      | 64            | Active | Simula resposta HTTP com dados fiscais fixos para testes de callouts, garantindo validação automatizada sem depender de serviços externos.                                                                                                                          |
| DwOpportunityFinishIntegrableBatch       | 64            | Active | Executa integração batch e agendada de oportunidades com sistema externo VEI_PROPOSTA, atualizando status e código externo, registrando logs HTTP e tratando erros para automação confiável.                                                                        |
| DWOppFinishIntegrable                    | 64            | Active | Integra oportunidades ao ERP via API REST POST, validando campos obrigatórios, gerando IDs externos e enviando dados formatados para automatizar sincronização e evitar erros.                                                                                      |
| DwOpportunityFinishIntegrableBatchTest   | 64            | Active | Classe de teste que simula dados e executa métodos do batch DwOpportunityFinishIntegrableBatch, validando integração e agendamento para atualizar status de oportunidades automaticamente.                                                                          |
| MockApiGetFinishSimulacao                | 64            | Active | Simula resposta HTTP JSON para testes de callouts, garantindo validação automatizada sem chamadas externas, melhorando confiabilidade e velocidade dos testes.                                                                                                      |
| CaseAttachmentAPI                        | 64            | Active | Expõe um endpoint REST que busca e retorna anexos de emails relacionados a um caso, codificando arquivos em base64 para facilitar integrações e visualização externa.                                                                                               |
| CaseAttachmentAPITest                    | 64            | Active | Testa a API REST que recupera anexos de EmailMessages vinculados a um Case, validando respostas corretas e erros para melhorar a automação e confiabilidade no acesso a arquivos.                                                                                   |
| DWAccountPJorPFIntegrable                | 64            | Active | Integra contas Salesforce com ERP via API REST POST, validando dados obrigatórios e diferenciando Pessoa Jurídica ou Física. Automatiza criação/atualização, melhorando sincronização e confiabilidade.                                                             |
| DwGetOFISolicitacaoIntegrableBatch       | 64            | Active | Executa integração batch e agendada para buscar dados de solicitações em WorkOrders via API externa, atualiza campos e registra logs, automatizando sincronização e melhorando dados para usuários.                                                                 |
| DWGetOFISolicitacaoIntegrable            | 64            | Active | Executa integração GET para consultar solicitações OFI via API externa, validando dados da WorkOrder e desserializando resposta JSON para uso em processos automatizados.                                                                                           |
| DW_GetOFISolicitacaoIntegrableTemplate   | 64            | Active | Define uma classe modelo que armazena dados de solicitações integráveis, facilitando o transporte estruturado dessas informações em processos automatizados.                                                                                                        |
| DwGetOFISolicitacaoIntegrableBatchTest   | 64            | Active | Cria dados de teste para contas, casos e ordens de serviço, executa métodos batch e agendados da integração DwGetOFISolicitacaoIntegrableBatch, validando processos automatizados.                                                                                  |
| DWReservaIntegrableResponseTemplate      | 64            | Active | Define um modelo de dados para armazenar informações de reserva integrável, facilitando a troca estruturada de dados entre sistemas ou processos automatizados.                                                                                                     |
| DwReservaIntegrable                      | 64            | Active | Classe integra reservas de estoque com ERP via API POST, construindo payload com dados atualizados de quantidade alocada. Automatiza sincronização de estoque, garantindo dados consistentes e atualizados.                                                         |
| DwReservaIntegrableBatch                 | 64            | Active | Executa em lote a integração de reservas de estoque pendentes via chamadas HTTP, atualiza status conforme sucesso ou erro, registra logs e permite agendamento automático para manter dados sincronizados.                                                          |
| DwReservaIntegrableBatchTest             | 64            | Active | Testa a integração batch de reservas de estoque, simulando dados e chamadas HTTP para validar processos automáticos de sincronização, agendamento e cancelamento da reserva.                                                                                        |
| DwReservaIntegrableMth2                  | 64            | Active | Classe integra reservas de estoque com ERP via API POST, monta JSON com dados de estoque e oportunidade, envia requisição e processa resposta, automatizando sincronização e melhorando controle de reservas.                                                       |
| DwReservaIntegrableMth2Batch             | 64            | Active | Executa integração batch e agendada das reservas de estoque pendentes, atualizando status conforme resposta externa e registrando logs HTTP para monitorar erros e sucessos.                                                                                        |
| DwReservaIntegrableMth2BatchTest         | 64            | Active | Classe de teste que simula dados e executa métodos do batch DwReservaIntegrableMth2Batch para validar integração e processamento de reservas de estoque, garantindo automação confiável.                                                                            |
| Log_Integracao_Formatar                  | 64            | Active | Formata e exibe o corpo da requisição e resposta de um log HTTP, melhorando a leitura e análise de integrações para usuários em páginas Visualforce.                                                                                                                |
| Log_Integracao_FormatarTest              | 64            | Active | Testa a classe Log_Integracao_Formatar ao inserir um registro de log HTTP, validando que os dados formatados são gerados corretamente para melhorar a visualização e análise de integrações.                                                                        |
| DWFormatter                              | 64            | Active | Formata texto JSON bruto em formato legível e indentado, melhorando a visualização de dados em interfaces ou logs para facilitar análise e depuração.                                                                                                               |
| OT_BusinessTimeActionTest                | 64            | Active | Testa a classe OT_BusinessTimeAction validando cálculo de tempo útil entre datas, garantindo precisão em horários comerciais e tratamento de datas inválidas para processos automatizados.                                                                          |
| OT_BusinessTimeAction                    | 64            | Active | Calcula horas trabalhadas e extras entre datas usando Business Hours AM/PM fornecidas. Facilita automação de controle de jornada e relatórios precisos no Flow.                                                                                                     |
| DWGetQTDEAlocadaReserva                  | 64            | Active | Classe integra com ERP via GET para consultar quantidade alocada em estoque, monta query dinâmica com dados de reserva e estoque, desserializa resposta JSON e facilita controle automatizado de reservas.                                                          |
| DW_Mercadao_ProductsTableController      | 64            | Active | Define um controlador global que implementa interface para obter produtos, mas atualmente retorna nulo, não impactando dados nem processos automatizados.                                                                                                           |
| MockApiGetReserva                        | 64            | Active | Simula uma resposta HTTP com JSON fixo para testes de callouts, garantindo validação automatizada sem depender de serviços externos.                                                                                                                                |
| DWIntegrableVEI_VEICULO                  | 64            | Active | Classe integra dados do objeto Asset (veículo) via API REST, validando campos obrigatórios, construindo payload JSON e enviando POST ao endpoint ERP. Automatiza sincronização de reservas e status, melhorando a consistência e atualização dos dados de veículos. |
| DWAtivoIntegrableBatch                   | 64            | Active | Executa integração batch de registros Asset com sistema externo via callouts, atualiza status conforme resposta, registra logs HTTP e permite agendamento e cancelamento automático.                                                                                |
| FlowAggregateDynamic                     | 64            | Active | Executa agregações dinâmicas (SUM, AVG, MAX, MIN, COUNT) via SOQL com filtros e agrupamentos, automatizando relatórios e análises personalizadas em fluxos Salesforce.                                                                                              |
| FlowAggregateDynamicUserTest             | 64            | Active | Testa a classe FlowAggregateDynamic para agregar dados do objeto User, validando contagem total e agrupada por ProfileId, garantindo operações corretas e tratamento de erros.                                                                                      |
| DWAtivoIntegrableResponseTemplate        | 64            | Active | Define um modelo simples para armazenar o status de resposta, facilitando o processamento e integração de dados em fluxos automatizados.                                                                                                                            |
| DWAtivoIntegrableBatchTest               | 64            | Active | Testa a classe DWAtivoIntegrableBatch simulando dados e chamadas HTTP, validando agendamento, execução síncrona e cancelamento do batch para garantir integração e atualização correta de ativos.                                                                   |
| MockApiAtivo                             | 64            | Active | Simula respostas HTTP com status 200 e corpo JSON fixo para testes de chamadas externas, garantindo validação automatizada sem depender de serviços reais.                                                                                                          |
| DwOpportunityLineIntegrableBatch         | 64            | Active | Executa integração batch e agendada de OpportunityLineItems, sincronizando dados com sistemas externos via callouts, atualizando status e registrando logs para automação e controle de erros.                                                                      |
| DWOppLineIntegrable                      | 64            | Active | Integra OpportunityLineItem com ERP via API REST POST, construindo JSON para criar ou atualizar peças balcão. Automatiza sincronização de dados e valida operações.                                                                                                 |
| DWCACIntegrableByOpp                     | 64            | Active | Integra oportunidades com sistema ERP via API REST POST, validando campos obrigatórios, gerando/atualizando IDs de contato e enviando dados estruturados para automatizar cadastro e atualização.                                                                   |
| DwOpportunityLineIntegrableBatchTest     | 64            | Active | Testa a integração batch de OpportunityLineItem com mock de API, criando dados de teste complexos para validar processos automatizados de sincronização e agendamento.                                                                                              |
| MockApiGetOppBalcao                      | 64            | Active | Simula respostas HTTP para testes de callouts, retornando dados JSON variados conforme parâmetros da requisição, facilitando validação automática sem chamadas externas reais.                                                                                      |
| BusinessHoursFlowAction                  | 64            | Active | Calcula horas úteis entre duas datas considerando o expediente definido, permitindo fluxos automatizados avaliarem prazos com precisão baseada em Business Hours.                                                                                                   |
| DW_CreateWorkPlanTemplateBatch           | 64            | Active | Executa em lote a criação automática de WorkPlanTemplates e regras de seleção associadas para Assets da marca 'valtra', garantindo templates ativos e sem duplicatas.                                                                                               |
| DWOFIAtendimentoIntegrableByOpp          | 64            | Active | Integra dados de oportunidades com sistema ERP via API POST, validando campos essenciais, construindo JSON com dados do contato e usuário, e definindo operação de inserção ou atualização.                                                                         |
| DWFATDADOADIntegrableByOpp               | 64            | Active | Integra dados adicionais da Opportunity via API REST POST ao ERP, validando campos essenciais e definindo operação (insert/update) para sincronizar informações e automatizar processos.                                                                            |
| BusinessHoursFlowAction_Tests            | 64            | Active | Testa a classe BusinessHoursFlowAction calculando intervalos dentro de diferentes horários comerciais, validando lógica para melhorar automações baseadas em horários e garantir precisão nos fluxos.                                                               |
| DW_CreateWorkPlanTemplateBatchTest       | 64            | Active | Classe de teste que executa o batch DW_CreateWorkPlanTemplateBatch, validando sua enfileiramento para automatizar a criação de templates de planos de trabalho.                                                                                                     |
| AtualizaPricebookEntryCodigoExternoBatch | 64            | Active | Atualiza em lote PricebookEntry vazios em DWCodigoExterno__c com o código externo do produto, garantindo dados consistentes para peças no Pricebook padrão.                                                                                                         |
| AtualizaPECodigoExternoBatchTest         | 64            | Active | Testa o batch AtualizaPricebookEntryCodigoExternoBatch que atualiza o campo DWCodigoExterno__c em PricebookEntry, garantindo dados externos sincronizados e processos automatizados confiáveis.                                                                     |
| DW_SetWPTToAIBatch                       | 64            | Active | Executa batch que busca até 50 WorkPlanTemplate não atualizados, envia seus IDs via callout HTTP para integração externa e marca registros como atualizados, automatizando sincronização.                                                                           |
| DW_SetWPTToAIMock                        | 64            | Active | Simula respostas HTTP com status 200 e corpo JSON para testes, permitindo validar chamadas externas sem afetar dados reais ou processos em produção.                                                                                                                |
| DW_SetWPTToAIBatchTest                   | 64            | Active | Testa a execução do batch DW_SetWPTToAIBatch com mock de callout HTTP, garantindo processamento assíncrono correto e confiável para atualizações automatizadas.                                                                                                     |
| DWOFIFormaPgtoIntegrableByOpp            | 64            | Active | Classe integra condições de pagamento vinculadas a oportunidades via API ERP, enviando dados validados em POST e atualizando registros conforme resposta, automatizando sincronização financeira.                                                                   |
| DWOFIFATFrenteCaixaIntegrableByOpp       | 64            | Active | Integra dados da oportunidade com sistema ERP via API REST POST, validando campos obrigatórios e enviando JSON customizado para automatizar faturamento no frente de caixa.                                                                                         |
| DWPECRomaneioIntegrable                  | 64            | Active | Classe integra dados de OpportunityLineItem com ERP via API REST, enviando POST para criar/atualizar romaneio, obtendo IDs e serializando JSON para automatizar sincronização de estoque.                                                                           |
| DWCallFullCaseIntegrable                 | 64            | Active | Enfileira chamadas assíncronas para integrar dados completos de casos e ordens de serviço, garantindo processamento sequencial e atualizações automatizadas via batch.                                                                                              |
| DWCallFullCaseIntegrableTest             | 64            | Active | Classe de teste que valida métodos e fila assíncrona da DWCallFullCaseIntegrable, garantindo execução correta e integridade em processos automatizados.                                                                                                             |
| DWUpdatePecaBalcaoIntegrableByOpp        | 64            | Active | Classe integra dados de itens de oportunidade com sistema ERP via API REST, enviando atualizações de estoque e compromissos. Automatiza sincronização, melhora precisão e agilidade no processamento de pedidos.                                                    |
| DW_NOXMercadaoController                 | 64            | Active | Verifica se há produtos com status 'integrando' em uma oportunidade, permitindo interfaces Lightning otimizarem exibição e processos automatizados reagirem a esse estado.                                                                                          |
| DW_NOXMercadaoControllerTest             | 64            | Active | Classe de teste que valida a execução do método getProdutosIntegrando, garantindo a integração correta de produtos para o usuário atual sem erros.                                                                                                                  |
| DWGETLocacaoIntegrableByOpp              | 64            | Active | Consulta dados de locação integrando com ERP via API GET, monta query SQL complexa para obter itens e preços por empresa, revenda e romaneio, e desserializa resposta JSON para uso em processos automatizados.                                                     |
| RelatorioConsolidadoController           | 64            | Active | Carrega um Work Order e seus Service Appointments vinculados, recupera relatórios e imagens de assinaturas anexadas, e organiza dados para exibir um relatório consolidado visual com assinaturas embutidas.                                                        |
| RelatorioConsolidadoTest                 | 64            | Active | Testa o controlador RelatorioConsolidadoController validando carregamento de WorkOrder, ServiceAppointments e assinaturas em PNG anexadas via ContentVersion, garantindo exibição correta no relatório consolidado.                                                 |
| PricebookEntryBatch                      | 65            | Active | Atualiza ou cria PricebookEntry para produtos do tipo "Peça", definindo preço fixo e códigos externos, garantindo preços padronizados e dados sincronizados no catálogo.                                                                                            |
| AtualizaDWCodigoExterno                  | 65            | Active | Atualiza lote de PricebookEntry preenchendo DWCodigoExterno__c com o código do produto quando vazio, garantindo dados consistentes para processos de vendas automatizados.                                                                                          |
| DW_UnlockBookingController               | 64            | Active | Consulta produtos com solicitações de reposição, detalha reservas e disponibilidades por empresa e revenda, e atualiza registros para automatizar controle de estoque e melhorar decisões.                                                                          |
| DwOFIPecaSolicitadaIntegrableBatch       | 63            | Active | Executa em lote a integração de WorkOrderLineItem com sistema externo via callouts, atualiza status e logs de integração, automatizando sincronização e melhorando controle de erros.                                                                               |
| DW_Mercadao_StockControllerTest          | 64            | Active | Classe de teste que valida métodos do controlador DW_Mercadao_StockController, garantindo execução correta e suporte confiável à consulta automatizada de estoque por produto.                                                                                      |
| DW_Mercadao_StockController              | 64            | Active | Consulta estoques filtrando por produtos, revenda e empresa da oportunidade; retorna mapa com quantidades disponíveis, otimizando decisões de venda e automações.                                                                                                   |
| DwOpportunityLineIntegrableOTBatch       | 63            | Active | Executa integração batch e agendada de OpportunityLineItems vinculados a uma Opportunity, atualiza status de integração, registra logs e sincroniza dados externos para automatizar processos de faturamento e atendimento.                                         |
| DwManyOFIPecaIntegrableBatch             | 64            | Active | Executa integração ativa de peças em WorkOrderLineItem com base em IDs recebidos, consultando dados relevantes e disparando processo automatizado para atualizar status e sincronizar informações.                                                                  |
| DwManyOFIServicoIntegrableBatch          | 64            | Active | Executa integração ativa para WorkOrderLineItems selecionados, consultando dados essenciais e disparando processo externo, automatizando atualização e sincronização de serviços.                                                                                   |
| DWOFIFormaPgtoOSIntegrableByOpp          | 63            | Active | Integra condições de pagamento de Ordens de Serviço via API ERP, validando dados e montando payload JSON para criar ou atualizar registros, automatizando sincronização e garantindo dados consistentes.                                                            |
| DWCallFullOTIntegrable                   | 64            | Active | Enfileira chamadas assíncronas para integrar ordens de trabalho, executando processos em sequência para atualizar dados e garantir sincronização automática com sistemas externos.                                                                                  |
| DwManyOFIPecaSolicitadaIntegrableBatch   | 64            | Active | Executa integração ativa de peças solicitadas em WorkOrderLineItem via batch, automatizando atualização e sincronização de dados para melhorar processos de OS.                                                                                                     |
| DW_UnlockBookingControllerTest           | 64            | Active | Testa o controlador DW_UnlockBookingController criando dados simulados para produtos, estoque e reservas; valida métodos que recuperam e atualizam solicitações de reposição, garantindo processos automatizados confiáveis.                                        |
| DwOpportunityLineIntegrableOTBatchTest   | 63            | Active | Testa a integração batch de OpportunityLine com WorkOrder via chamadas HTTP simuladas, criando dados complexos para validar processos automatizados e garantir atualização correta de status.                                                                       |
| DwManyOFIPecaSolicitadaInteBatchTest     | 64            | Active | Testa a execução do batch DwManyOFIPecaSolicitadaIntegrableBatch com o usuário atual, validando processamento automatizado e garantindo integridade dos dados em lote.                                                                                              |
| DwManyOFIServicoIntegrableBatchTest      | 64            | Active | Classe de teste que executa o método main do batch DwManyOFIServicoIntegrableBatch, validando sua execução para garantir processos automatizados sem erros.                                                                                                         |
| DwManyOFIPecaIntegrableBatchTest         | 64            | Active | Testa a execução do batch DwManyOFIPecaIntegrableBatch com o usuário atual, garantindo que o processo automatizado de integração rode corretamente sem erros.                                                                                                       |
| DWCallFullOTIntegrableTest               | 64            | Active | Classe de teste que valida o método getOTIds da classe DWCallFullOTIntegrable, garantindo a correta recuperação de IDs de OT para o usuário atual.                                                                                                                  |
| RelatorioConsolidadoControllerTest       | 64            | Active | Testa o RelatorioConsolidadoController criando dados relacionados (WorkOrder, ServiceAppointment, ServiceReport, assinaturas) para validar carregamento correto e tratamento de erro sem parâmetro id.                                                              |
| DwOFIPecaSolicitadaIntegrableBatchTest   | 63            | Active | Classe de teste que simula dados e executa métodos do batch DwOFIPecaSolicitadaIntegrableBatch, validando integração e agendamento de processamento de peças solicitadas.                                                                                           |
| DW_OpportunityGlobalDiscountCtrl         | 61            | Active | Fornece dados da Oportunidade e seus itens para LWC e atualiza descontos dos itens de forma transacional, garantindo que todos os descontos sejam validados e aplicados juntos ou nenhum é salvo.                                                                   |
| DW_OpportunityGlobalDiscountCtrlTest     | 64            | Active | Testa métodos da classe DW_OpportunityGlobalDiscountCtrl que obtêm contexto da oportunidade e atualizam descontos em itens, garantindo automação correta de descontos em vendas.                                                                                    |
| DWOpportunityDraftTypingController       | 63            | Active | Executa upsert de oportunidades, itens de linha e condições de pagamento via AuraEnabled, facilitando salvamentos rápidos e tratamento de erros para interfaces Lightning.                                                                                          |
| DWOpportunityDraftTypingControllerTest   | 63            | Active | Testa métodos de upsert da classe DWOpportunityDraftTypingController, validando inserção de oportunidades, itens e condições de pagamento, e garantindo tratamento de exceções para entradas nulas.                                                                 |
| DW_OpportunityPaymentConditionDTO        | 63            | Active | Define um DTO que permite Flows e componentes Lightning transferirem dados estruturados de condições de pagamento, facilitando automações e processamento financeiro em oportunidades.                                                                              |
| DW_TokenISOIntegrable                    | 65            | Active | Executa integração POST para obter token via API ISO, monta corpo com credenciais codificadas, processa resposta JSON e armazena token para uso em chamadas automatizadas.                                                                                          |
| DW_TokenISOIntegrableResponse            | 65            | Active | Define estrutura para armazenar token de acesso OAuth, facilitando autenticação automática em integrações externas e melhorando processos de autorização sem intervenção do usuário.                                                                                |
| DW_ISO_GETStatusIntegrable               | 65            | Active | Executa requisição GET para obter status de um ativo via API externa, validando chassi e gerando token de acesso. Automatiza integração e atualiza dados do equipamento.                                                                                            |
| DW_ISOGetStatusResponse                  | 65            | Active | Classe vazia sem métodos ou propriedades; não executa ações nem impacta processos ou experiência do usuário.                                                                                                                                                        |
| DW_GETISOIntegrableBatch                 | 65            | Active | Executa em lote a integração de Assets com sistema ISO via callouts, atualizando localização, horímetro e status; registra logs e agenda execuções automáticas para manter dados sincronizados.                                                                     |
| DW_ISO_GETDTCIntegrable                  | 65            | Active | Executa integração GET para obter falhas de um ativo via API externa, validando chassi, gerando token de acesso e retornando resposta JSON para automatizar monitoramento de equipamentos.                                                                          |
| DW_GETISOIntegrableBatchTest             | 65            | Active | Classe de teste que simula chamadas HTTP e cria dados de contas, ativos e condições de pagamento para validar a execução e agendamento do batch DwAccountIntegrableBatch, garantindo integração correta e automatização confiável.                                  |
| DWGetISOMock                             | 65            | Active | Simula uma resposta HTTP JSON para testes, fornecendo dados de equipamento fictícios que permitem validar integrações sem chamadas externas, garantindo testes automatizados confiáveis.                                                                            |
| LightningSelfRegisterController          | 65            | Active | Controla o auto-registro de usuários na comunidade, validando dados e senha, criando usuários com campos extras, e redirecionando após registro para melhorar a experiência e automatizar o cadastro.                                                               |
| LightningForgotPasswordController        | 65            | Active | Controla o processo de recuperação de senha em Lightning, valida usuário, dispara reset via Site.forgotPassword e redireciona para página de confirmação, melhorando a experiência do usuário.                                                                      |
| LightningLoginFormController             | 65            | Active | Controla o login Lightning em Experience Cloud, executa autenticação via Site.login, gerencia URLs de registro e recuperação, e configura o contexto da experiência para automatizar acesso e navegação.                                                            |
| LightningLoginFormControllerTest         | 65            | Active | Testa a classe LightningLoginFormController, validando configurações de login, registro e autenticação para garantir comportamentos corretos na experiência de autenticação do usuário.                                                                             |
| LightningForgotPasswordControllerTest    | 65            | Active | Testa o controlador de recuperação de senha, validando respostas a nomes de usuário inválidos e URLs nulas, garantindo tratamento correto de erros e instância do controlador.                                                                                      |
| LightningSelfRegisterControllerTest      | 65            | Active | Testa métodos do LightningSelfRegisterController, validando senhas, fluxo de auto-registro com dados válidos e inválidos, e manipulação de campos extras, garantindo robustez na experiência de auto-registro.                                                      |
| UpdatePricebookEntriesBatch              | 64            | Active | Atualiza em lote PricebookEntries filtrados, combinando código externo do produto com valor de qualificador por perfil cliente, garantindo dados consistentes e automatizando ajustes de filial.                                                                    |
| UpdatePricebookEntriesBatchTest          | 64            | Active | Testa o batch UpdatePricebookEntriesBatch que atualiza o campo DWCodigoFilial__c em PricebookEntry com valores de qualificadores, garantindo dados corretos e automação confiável.                                                                                  |
| UpdatePricebookEntriesBatchInvocable     | 64            | Active | Executa um batch via método invocável para atualizar o campo DWCodigoFilial__c em PricebookEntry, automatizando a atualização em massa e integrando-se a fluxos Salesforce.                                                                                         |
| UpdatePricebookEntriesBatchInvokerTest   | 64            | Active | Testa a invocação do batch UpdatePricebookEntriesBatchInvocable, garantindo execução correta e suporte a processos automatizados de atualização de PricebookEntries.                                                                                                |
| MissingStandardPricebookEntriesBatch     | 64            | Active | Cria entradas ativas no Pricebook padrão para produtos com custo definido que ainda não possuem, garantindo catálogo atualizado e facilitando vendas automáticas.                                                                                                   |
| MissingStandardPricebookEntriesBatchTest | 64            | Active | Testa o batch que insere entradas faltantes de produtos ativos no Pricebook padrão, garantindo que produtos com custo definido sejam corretamente adicionados ao catálogo.                                                                                          |
| DWScheduledCallApiGetOFICONDATest        | 64            | Active | Testa a execução agendada da classe DWScheduledCallApiGetOFICONDAtendimento, simulando dados e chamada HTTP para validar integração e atualização automática via job Cron.                                                                                          |
| DWScheduledCallApiGetOFICONDAtendimento  | 64            | Active | Agenda a execução assíncrona do job DW_GetOFICONDAtendimentoByERPQueueable, permitindo chamadas externas para atualizar dados de atendimento automaticamente.                                                                                                       |
| DW_GetOFICONDAtendimentoByERPQueueable   | 64            | Active | Executa integração assíncrona para buscar atendimentos via API externa, atualiza Assets e Cases no Salesforce, registra logs e enfileira próximas execuções para paginar dados.                                                                                     |
| DWIntegrableOFI_Servico_OS               | 64            | Active | Classe integra itens de serviço de Ordem de Serviço via API externa, validando dados obrigatórios, construindo payload JSON e definindo headers para inserir ou atualizar registros no ERP.                                                                         |
| UpdateAmarracaoBatch                     | 64            | Active | Executa em lote a atualização do campo AmarracaoNPX de 'Amarrado' para 'Desamarrado' em PricebookEntry, automatizando a limpeza periódica via agendamento para manter dados atualizados.                                                                            |
| UpdateAmarracaoBatchTest                 | 64            | Active | Testa o batch UpdateAmarracaoBatch que atualiza o campo customizado DW_NPX__AmarracaoNPX__c de 'Amarrado' para 'Desamarrado' em PricebookEntry, garantindo dados corretos e automatização.                                                                          |
| BatchGetWorkOrderSemCasoMeThodTest       | 64            | Active | Testa a integração do batch BatchGetWorkOrderSemCaso com WorkOrders, simulando chamadas HTTP, criando dados relacionados e validando execuções síncronas e agendadas para garantir atualização correta.                                                             |
| BatchGetWorkOrderSemCasoMethod2          | 64            | Active | Executa em batch a integração de WorkOrders sem caso, busca dados externos via callout, atualiza Assets e Cases relacionados, registra logs e agenda novos processos para manter dados sincronizados.                                                               |
| VerticalPriceHandler                     | 64            | Active | Atualiza o campo DW_NPX__AmarracaoNPX__c para "Desamarrado" em PricebookEntry, automatizando a marcação de itens para melhorar o controle de preços vinculados.                                                                                                     |
| VerticalPriceHandlerTest                 | 64            | Active | Testa a classe VerticalPriceHandler validando a obtenção de campos e a atualização do campo AmarracaoNPX em PricebookEntry, garantindo dados corretos e processos automatizados confiáveis.                                                                         |
| SiteLoginController                      | 60            | Active | Controla o login de usuários em sites públicos, capturando usuário e senha, e executa a autenticação via Site.login, redirecionando para a URL inicial após o acesso.                                                                                               |
| SiteLoginControllerTest                  | 60            | Active | Testa o SiteLoginController simulando login com credenciais fixas, validando a funcionalidade de autenticação do site para garantir processos de login automatizados.                                                                                               |
| SiteRegisterController                   | 60            | Active | Cria usuários de portal vinculados a uma conta específica, valida senhas, registra e autentica automaticamente, facilitando o autoatendimento e acesso imediato ao portal.                                                                                          |
| SiteRegisterControllerTest               | 60            | Active | Testa a classe SiteRegisterController validando o registro de usuário com dados inválidos, garantindo que falhas no cadastro sejam corretamente tratadas.                                                                                                           |
| ChangePasswordController                 | 60            | Active | Controla a troca de senha no site, recebendo senhas antiga e nova, e executa a alteração via Site.changePassword, automatizando a atualização segura do usuário.                                                                                                    |
| ChangePasswordControllerTest             | 60            | Active | Testa a classe ChangePasswordController validando a troca de senha com senhas antigas e novas, garantindo a funcionalidade e prevenindo falhas no processo de alteração.                                                                                            |
| ForgotPasswordController                 | 60            | Active | Controla a funcionalidade de recuperação de senha no site, acionando o reset via Site.forgotPassword(username) e redirecionando à página de confirmação ao sucesso.                                                                                                 |
| ForgotPasswordControllerTest             | 60            | Active | Testa a funcionalidade de recuperação de senha do site, validando que o método forgotPassword() processa corretamente o usuário informado, garantindo a automação da recuperação.                                                                                   |
| MyProfilePageController                  | 60            | Active | Controla a edição do perfil do usuário logado, bloqueia acesso de convidados, permite modificar e salvar dados pessoais, e direciona para a página de troca de senha.                                                                                               |
| MyProfilePageControllerTest              | 60            | Active | Testa a edição e salvamento dos dados do usuário portal, validando mudanças no campo Fax e controle do modo edição, garantindo atualização correta e fluxo de edição funcional.                                                                                     |
| CommunitiesLoginController               | 60            | Active | Controla o login em comunidades, redirecionando usuários à página de autenticação com URLs personalizadas, otimizando o fluxo de acesso em sites públicos.                                                                                                          |
| CommunitiesLoginControllerTest           | 60            | Active | Classe de teste que valida o método de redirecionamento de login da CommunitiesLoginController, garantindo o fluxo correto na autenticação do usuário no site.                                                                                                      |
| CommunitiesLandingController             | 60            | Active | Redireciona usuários automaticamente para a página inicial correta em comunidades Salesforce, garantindo acesso adequado conforme suas credenciais ao carregar a página.                                                                                            |
| CommunitiesLandingControllerTest         | 60            | Active | Testa a classe CommunitiesLandingController garantindo que o redirecionamento inicial baseado em credenciais funcione, validando a navegação correta para melhorar fluxos automatizados.                                                                            |
| CommunitiesSelfRegController             | 60            | Active | Controla o auto cadastro de usuários em comunidades, valida senhas, cria usuários externos e realiza login automático ou redireciona para confirmação, automatizando o registro e melhorando a experiência.                                                         |
| CommunitiesSelfRegControllerTest         | 60            | Active | Testa a classe de registro automático em comunidades, validando que o método de registro falha fora do contexto de usuário convidado e com senhas não coincidentes.                                                                                                 |
| CommunitiesSelfRegConfirmController      | 60            | Active | Controla a navegação do usuário para a página inicial correta conforme suas credenciais, direcionando acessos e otimizando o fluxo de login em comunidades Salesforce.                                                                                              |
| CommunitiesSelfRegConfirmControllerTest  | 60            | Active | Testa a criação do controlador CommunitiesSelfRegConfirmController, garantindo que a navegação inicial do usuário ocorra conforme suas credenciais, suportando fluxos de registro automático.                                                                       |
| MicrobatchSelfRegController              | 60            | Active | Controla o auto-registro assíncrono de usuários na comunidade, criando User, Contact e Account; trata erros exibindo mensagens e redireciona para página de confirmação.                                                                                            |
| MicrobatchSelfRegControllerTest          | 60            | Active | Testa a classe MicrobatchSelfRegController simulando registro de usuário; valida que registerUser retorna null fora do contexto de usuário convidado, garantindo fluxo correto.                                                                                     |
| CheckRequiredDocumentsCalculator         | 61            | Active | Calcula documentos obrigatórios e opcionais para um registro, avaliando critérios dinâmicos e anexos válidos, para orientar usuários sobre pendências documentais e automatizar validações.                                                                         |
| CheckRequiredDocumentsCalculatorTest     | 61            | Active | Testa a lógica que calcula documentos obrigatórios e opcionais anexados ou faltantes para uma conta, validando regras por perfil e qualificadores para automatizar controle documental.                                                                             |
| CheckRequiredDocumentsInvocable          | 61            | Active | Verifica documentos obrigatórios e opcionais anexados a registros, identifica faltantes ou irregulares, e retorna listas detalhadas para automatizar validações e alertar usuários.                                                                                 |
| CopyOrderToOpportunityService            | 61            | Active | Atualiza ou cria Oportunidades vinculadas a Pedidos marcados para replicação, sincronizando valores e estágio "Ganha" automaticamente para agilizar vendas e garantir dados consistentes.                                                                           |
| CopyOrderToOpportunityServiceTest        | 61            | Active | Testa a criação automática de uma Oportunidade ao copiar dados de um Pedido com itens, validando vínculo, valores e estágios para garantir processos de vendas integrados e precisos.                                                                               |
| DWAccountABCCurveSchedule                | 59            | Active | Agenda a execução diária para classificar contas em curvas ABC (A, B, C) com base no faturamento acumulado das oportunidades ganhas nos últimos 180 dias, atualizando o campo DWCurvaABC__c.                                                                        |
| DWAccountABCCurveScheduleTest            | 59            | Active | Testa o agendamento da classe DWAccountABCCurveSchedule simulando oportunidades com estágios abertos e fechados, produtos e contas, garantindo execução correta do processo automatizado.                                                                           |
| DWCPMRecalcPeriodoTituloBatch            | 59            | Active | Atualiza em lote o campo Período__c de DWTitulo__c com base na proximidade da DataVencimento__c, classificando títulos por faixas de dias para facilitar filtros e relatórios.                                                                                      |
| DWCPMRecalcPeriodoTituloSchedule         | 59            | Active | Agenda a execução imediata do batch DWCPMRecalcPeriodoTituloBatch com lote de 2000 registros, automatizando o recálculo de períodos de títulos em massa.                                                                                                            |
| DWControllerSintegraWS                   | 55            | Active | Classe expõe métodos AuraEnabled que consultam APIs externas (Sintegra, Receita Federal) para obter dados fiscais e cadastrais, retornando respostas JSON para interfaces Lightning e automatizações.                                                               |
| DWControllerSintegraWSTest               | 56            | Active | Testa a chamada HTTP simulada para obter saldo Sintegra, garantindo que a integração externa funcione corretamente e automatize validações sem afetar dados reais.                                                                                                  |
| DWCustomProposalController               | 58            | Active | Controla propostas customizadas carregando dados detalhados de Opportunity ou Quote, configura layouts PDF via metadata, formata endereços e valores, e agrega imagens de produtos para gerar propostas automatizadas e personalizadas.                             |
| DWCustomProposalControllerTest           | 58            | Active | Testa o controlador DWCustomProposalController criando dados simulados (conta, contato, oportunidade, produto, cotação) e valida formatações de endereço, datas, itens e moeda, garantindo exibição correta em propostas.                                           |
| DWPNPDeleteStandardItensFromOrderTest    | 61            | Active | Testa a remoção automática de itens genéricos padrão em pedidos, garantindo que apenas produtos não genéricos permaneçam, otimizando a precisão dos dados do pedido.                                                                                                |
| DWSintegraRFPFResponseTemplate           | 61            | Active | Deserializa JSON da resposta do serviço Sintegra PF, extraindo dados pessoais e cadastrais para automatizar validações e enriquecer registros de clientes.                                                                                                          |
| DWSintegraRFPJResponseTemplate           | 61            | Active | Deserializa JSON da API Sintegra para estruturar dados detalhados de empresas, facilitando integração e automação de consultas cadastrais no Salesforce.                                                                                                            |
| DWSintegraSFResponseTemplate             | 61            | Active | Deserializa JSON da API Sintegra, estruturando dados cadastrais empresariais para uso em processos automatizados e exibição detalhada ao usuário.                                                                                                                   |
| DWSintegraSNResponseTemplate             | 61            | Active | Define um modelo para desserializar respostas JSON da consulta Sintegra, extraindo dados empresariais e status do Simples Nacional, facilitando integração e automação de validações.                                                                               |
| DWSintegraSTResponseTemplate             | 61            | Active | Deserializa JSON da consulta Sintegra, estruturando dados cadastrais empresariais para automatizar validação e exibir informações fiscais detalhadas ao usuário.                                                                                                    |
| DW_AuraLWCHelper                         | 52            | Active | Executa consultas, inserções, atualizações e exclusões de registros via LWC, suportando relacionamentos; melhora automação e interação dinâmica com dados Salesforce.                                                                                               |
| DW_AuraLWCHelperTest                     | 52            | Active | Testa métodos da classe DW_AuraLWCHelper que recuperam, atualizam e deletam registros Account e Contact, validando sucesso e erros para garantir automação confiável e dados consistentes.                                                                          |
| DW_CheckAndFormatBRDocFlowHelper         | 59            | Active | Valida e formata documentos CPF ou CNPJ recebidos, removendo caracteres inválidos, confirmando validade e aplicando máscara padrão, garantindo dados corretos e padronizados em automações.                                                                         |
| DW_CheckAndFormatBRDocFlowHelperTest     | 59            | Active | Testa a validação e formatação automática de documentos brasileiros (CPF/CNPJ), garantindo dados corretos e padronizados para melhorar processos e experiência do usuário.                                                                                          |
| DW_CheckAndFormatFlowHelper              | 59            | Active | Valida e formata textos via regex em fluxos, limpando dados, verificando conformidade e aplicando formatação, automatizando validação e padronização de entradas do usuário.                                                                                        |
| DW_CheckAndFormatFlowHelperTest          | 59            | Active | Testa o método checkAndFormat da classe DW_CheckAndFormatFlowHelper, validando e formatando números via regex para garantir dados consistentes em fluxos automatizados.                                                                                             |
| DW_CloneOLIQueuable                      | 62            | Active | Clona itens de linha de oportunidade em lote via fila, opcionalmente apaga itens antigos, atualiza status na oportunidade e reencadeia até concluir, automatizando replicação de dados.                                                                             |
| DW_CloneOLIQueuableTest                  | 62            | Active | Testa a fila DW_CloneOLIQueuable que clona OpportunityLineItems, opcionalmente exclui originais, e atualiza status na Opportunity, automatizando duplicação de itens e controle de erros.                                                                           |
| DW_CloneOpportunityController            | 62            | Active | Clona oportunidades com campos personalizados e opcionalmente seus contatos e produtos, automatizando replicação e facilitando criação rápida de registros relacionados.                                                                                            |
| DW_CloneOpportunityControllerTest        | 62            | Active | Testa a clonagem avançada de oportunidades, replicando dados e listas relacionadas (contatos e produtos), garantindo integridade e automação na duplicação de registros para acelerar vendas.                                                                       |
| DW_ConditionOptions                      | 50            | Active | Define opções fixas de tipos de condição (texto, número, data, booleano, nulo) para uso consistente em filtros ou regras, padronizando processos automatizados.                                                                                                     |
| DW_DataBootController                    | 61            | Active | Controla a inicialização e atualização em massa de dados (contas, contatos, produtos, pedidos) via API Aura, garantindo relacionamentos corretos e integridade com upserts e tratamento de PricebookEntry e OrderItem.                                              |
| DW_Exception                             | 50            | Active | Define uma exceção personalizada DW_Exception para capturar e tratar erros específicos, facilitando o controle e a depuração em processos automatizados.                                                                                                            |
| DW_ExceptionTest                         | 51            | Active | Classe de teste que valida a geração e captura da exceção personalizada DW_Exception, garantindo tratamento correto de erros em processos automatizados.                                                                                                            |
| DW_FieldCollector                        | 51            | Active | Coleta e retorna todos os nomes de campos de um objeto Salesforce, facilitando a geração dinâmica de listas ou consultas para processos automatizados e interfaces.                                                                                                 |
| DW_Helper                                | 51            | Active | Valida strings e objetos para detectar valores nulos ou vazios, facilitando checagens seguras e conversão de strings numéricas em inteiros, otimizando lógica e evitando erros.                                                                                     |
| DW_HelperTest                            | 51            | Active | Classe de teste que valida métodos utilitários DW_Helper para verificar valores nulos ou vazios em campos de Opportunity, garantindo a confiabilidade das validações usadas em processos automatizados.                                                             |
| DW_Integrable                            | 54            | Active | Define uma classe abstrata que padroniza chamadas HTTP para integrações externas, construindo requisições, enviando-as, tratando respostas e erros, automatizando comunicação API.                                                                                  |
| DW_IntegrableHelper                      | 53            | Active | Tenta salvar registros via upsert; se falhar, publica erros em posts no Chatter, removendo posts antigos relacionados. Automatiza feedback de falhas para usuários.                                                                                                 |
| DW_IntegrableHelperTest                  | 56            | Active | Testa a classe DW_IntegrableHelper ao tentar salvar uma conta com nome nulo e postar mensagem no Chatter, validando tratamento de erros e integridade dos dados.                                                                                                    |
| DW_IntegrableTest                        | 55            | Active | Testa integrações HTTP simulando chamadas GET, POST e PUT com endpoints e headers fixos, garantindo que processos automatizados de integração funcionem corretamente.                                                                                               |
| DW_IntegrableTestMock                    | 55            | Active | Simula respostas HTTP para chamadas externas em testes, retornando dados de Account mockados ao detectar endpoint específico, facilitando testes automatizados sem dependência externa.                                                                             |
| DW_OperatorOptions                       | 50            | Active | Define operadores lógicos (AND, OR) para uso em filtros ou regras, facilitando a construção dinâmica de condições em processos automatizados ou interfaces.                                                                                                         |
| DW_ParentRelationship                    | 51            | Active | Cria instâncias que coletam campos de um objeto relacionado e gera strings para consultas SOQL, facilitando a inclusão automática de campos de objetos pai em queries.                                                                                              |
| DW_QueryCondition                        | 50            | Active | Constrói condições dinâmicas para consultas SOQL, formatando filtros por tipo (string, número, data, booleano) e combinando operadores lógicos, facilitando consultas automatizadas flexíveis.                                                                      |
| DW_QueryConditionComposition             | 51            | Active | Define estruturas compostas de condições de consulta, combinando listas e subcondições com operadores AND/OR para construir filtros dinâmicos e reutilizáveis em consultas automatizadas.                                                                           |
| DW_QueryFactory                          | 50            | Active | Constrói e executa consultas SOQL dinâmicas com múltiplas condições, relacionamentos e limites, facilitando consultas complexas e otimizando processos automatizados no Salesforce.                                                                                 |
| DW_QueryFactoryTest                      | 50            | Active | Testa a DW_QueryFactory para construir e executar consultas SOQL complexas em Opportunity, combinando condições, operadores lógicos, relacionamentos e limites, automatizando validações de dados.                                                                  |
| DW_Relationship                          | 51            | Active | Cria instâncias para representar relacionamentos entre objetos, gera subqueries SOQL para consultas aninhadas, facilitando a recuperação automatizada de dados relacionados.                                                                                        |
| DW_RequestFactory                        | 48            | Active | Constrói e envia requisições HTTP (GET, POST, PUT, PATCH) com parâmetros e cabeçalhos configuráveis, registra logs da requisição e resposta, facilitando integrações externas e monitoramento.                                                                      |
| DW_RequestFactoryAura                    | 52            | Active | Classe expõe método Aura que realiza requisição GET a um endpoint, retornando o corpo da resposta para uso em componentes Lightning, facilitando integrações e automações via UI.                                                                                   |
| DW_RequestFactoryAuraTest                | 52            | Active | Testa a chamada HTTP simulada em DW_RequestFactoryAura, garantindo que getURL funcione corretamente sem chamadas externas, melhorando a confiabilidade dos testes automatizados.                                                                                    |
| DW_RequestFactoryTest                    | 49            | Active | Testa a classe DW_RequestFactory simulando chamadas HTTP POST, GET, PUT e PATCH com cabeçalhos, parâmetros e corpo, garantindo a automação confiável de integrações externas.                                                                                       |
| DW_RequestFactoryTestMock                | 52            | Active | Simula respostas HTTP com status 200 em testes, permitindo validar chamadas externas sem executar requisições reais, agilizando testes automatizados e garantindo confiabilidade.                                                                                   |
| DW_ResponseHTTP                          | 52            | Active | Padroniza respostas HTTP JSON, indicando sucesso ou erro com dados ou mensagens, facilitando tratamento consistente de resultados em integrações e APIs.                                                                                                            |
| DW_ResponseHTTPTest                      | 52            | Active | Testa métodos da classe DW_ResponseHTTP simulando respostas de sucesso e erro com registros Account, garantindo que o tratamento HTTP funcione corretamente em processos automatizados.                                                                             |
| DW_SObjectService                        | 57            | Active | Classe abstrata que inicializa listas e mapas de registros novos e antigos em triggers, facilitando comparações e atualizações automáticas de dados durante processos automatizados.                                                                                |
| DW_SintegraResponse_CPF                  | 55            | Active | Deserializa JSON de resposta do Sintegra para CPF, extraindo dados cadastrais e status, facilitando validação automática e exibição precisa ao usuário.                                                                                                             |
| DW_SintegraResponse_CPFTest              | 55            | Active | Testa a classe DW_SintegraResponse_CPF ao validar o parsing de JSON com dados de CPF, garantindo a correta conversão para objeto e suporte confiável a processos automatizados.                                                                                     |

# Relatórios

| Nome                                     | Nome de API                                              | Pasta                                  | Descrição                                                                                                                                          |
| ---------------------------------------- | -------------------------------------------------------- | -------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------- |
| Produtos com alocações                   | ProdutoAlocacoes                                         | Produtos                               | -                                                                                                                                                  |
| Gestão de devoluções - Merc Rio Preto    | Gesto_de_devolues_Merc_Rio_Preto_B51                     | Gestão de dev. - Mercadão Rio Preto    | -                                                                                                                                                  |
| excluir depois                           | excluir_depois_sm0                                       | Relatórios privados                    | -                                                                                                                                                  |
| excluir                                  | excluir_3FO                                              | Relatórios privados                    | -                                                                                                                                                  |
| Sales Person Activity                    | Sales_Person_Activity                                    | Sales and Marketing Reports            | -                                                                                                                                                  |
| Sales Exec Pipeline                      | Sales_Exec_Open_Pipeline                                 | Sales and Marketing Reports            | -                                                                                                                                                  |
| Marketing Exec Leads by Source           | LeadsbySource                                            | Sales and Marketing Reports            | -                                                                                                                                                  |
| ES: Average Deal Size                    | ES_Average_Deal_Size                                     | Getting Started - Executive Sponsor    | -                                                                                                                                                  |
| ES: Closed Lost Opportunities FYTD       | ES_Closed_Lost_Opportunities_FYTD                        | Getting Started - Executive Sponsor    | -                                                                                                                                                  |
| ES: Closed Won Opportunities By FY/Month | ES_Closed_Won_By_FY_Month                                | Getting Started - Executive Sponsor    | Closed Won opportunity by defined range                                                                                                            |
| ES: Closed Won Opportunities By FY/QT    | ES_Closed_Won_By_FY_Quarter                              | Getting Started - Executive Sponsor    | -                                                                                                                                                  |
| ES: FYTD Open Opportunities by Acct      | ES_FYTD_Open_Opps_by_Acct                                | Getting Started - Executive Sponsor    | -                                                                                                                                                  |
| ES: FYTD Won Opportunities by Acct       | ES_FYTD_Won_Opps_by_Acct                                 | Getting Started - Executive Sponsor    | -                                                                                                                                                  |
| ES: Open Opportunities                   | ES_Open_Opportunities                                    | Getting Started - Executive Sponsor    | -                                                                                                                                                  |
| ES: Open Opportunities in the Pipeline   | ES_Open_Opportunities_in_the_Pipeline                    | Getting Started - Executive Sponsor    | -                                                                                                                                                  |
| ES: Total Win Ratio                      | ES_Total_Win_Ratio                                       | Getting Started - Executive Sponsor    | -                                                                                                                                                  |
| KPI: Average Days to Close               | KPI_Average_Days_to_Close                                | Getting Started - Company KPI          | -                                                                                                                                                  |
| KPI: Average Deal Size                   | KPI_Average_Deal_Size                                    | Getting Started - Company KPI          | -                                                                                                                                                  |
| KPI: Closed Won Opptys By FY/Month       | KPI_Closed_Won_By_FY_Month                               | Getting Started - Company KPI          | -                                                                                                                                                  |
| KPI: Closed Won Opportunities By FY/QT   | KPI_Closed_Won_By_FY_QT                                  | Getting Started - Company KPI          | -                                                                                                                                                  |
| KPI: Open Opportunities in the Pipeline  | KPI_Open_Opportunities_in_the_Pipeline                   | Getting Started - Company KPI          | -                                                                                                                                                  |
| KPI: Total Win Ratio                     | KPI_Total_Win_Ratio                                      | Getting Started - Company KPI          | -                                                                                                                                                  |
| KPI: Closed Won and >=70% Prob Opptys    | KPI_Won_Plus_70_Probability                              | Getting Started - Company KPI          | -                                                                                                                                                  |
| SM: Closed Won Opptys This FY by Rep     | Closed_Won_This_FY_by_Owner_6qB                          | Getting Started - Sales Manager        | -                                                                                                                                                  |
| SM: New Activities Leaderboard           | New_Activities_Leaderboard_9ZT                           | Getting Started - Sales Manager        | -                                                                                                                                                  |
| SM: New Opportunities Leaderboard        | New_Opptys_Leaderboard_p5H                               | Getting Started - Sales Manager        | -                                                                                                                                                  |
| SM: Average Days to Close                | SM_Average_Days_to_Close                                 | Getting Started - Sales Manager        | -                                                                                                                                                  |
| SM: Average Deal Size                    | SM_Average_Deal_Size_X58                                 | Getting Started - Sales Manager        | Closed Won opportunity by defined range                                                                                                            |
| SM: Closed Won Opportunities By FY/Month | SM_Closed_Won_By_FYMonth_m1S                             | Getting Started - Sales Manager        | Closed Won opportunity by FY for Team                                                                                                              |
| SM: Closed Won Opportunities This Month  | SM_Closed_Won_This_M_by_Type_hUc                         | Getting Started - Sales Manager        | -                                                                                                                                                  |
| SM: Closed Won Opportunities This QT     | SM_Closed_Won_This_Q_by_Type_h88                         | Getting Started - Sales Manager        | -                                                                                                                                                  |
| SM: Open Opportunities in the Pipeline   | SM_Open_Opportunities_in_the_Pipeline_9H9                | Getting Started - Sales Manager        | -                                                                                                                                                  |
| SM: Win Ratio Current FY                 | SM_Win_Ratio_Current_FY_JUg                              | Getting Started - Sales Manager        | -                                                                                                                                                  |
| SR: Top Accounts by Revenue Amt          | My_Top_Accounts_PHw                                      | Getting Started - Sales Representative | -                                                                                                                                                  |
| SR: Activities Past Due on Opportunities | SR_Clean_your_Room                                       | Getting Started - Sales Representative | -                                                                                                                                                  |
| SR: Closed Won Opportunities By FY/Month | SR_Closed_Won_By_FYMonth_MdW                             | Getting Started - Sales Representative | Closed Won opportunity by defined range                                                                                                            |
| SR: Closed Won Opportunities MTD         | SR_Closed_Won_MTD                                        | Getting Started - Sales Representative | -                                                                                                                                                  |
| SR: Closed Won Oppty This QT             | SR_Closed_Won_This_Q_by_Type_dCK                         | Getting Started - Sales Representative | -                                                                                                                                                  |
| SR: Neglected Accounts                   | SR_Neglected_Accounts                                    | Getting Started - Sales Representative | -                                                                                                                                                  |
| SR: Open Opportunities in the Pipeline   | SR_Open_Opportunities_in_the_Pipeline                    | Getting Started - Sales Representative | -                                                                                                                                                  |
| SR: Stuck Opportunities Report           | SR_Stuck_Opportunities_Report                            | Getting Started - Sales Representative | -                                                                                                                                                  |
| Age of Cases Currently Open by Type      | Age_of_Cases_Currently_Open_by_Type                      | Service Dashboards Reports             | -                                                                                                                                                  |
| Aged Cases by Account                    | Aged_Cases_by_Account                                    | Service Dashboards Reports             | -                                                                                                                                                  |
| Aged Cases by Agent                      | Aged_Cases_by_Agent                                      | Service Dashboards Reports             | -                                                                                                                                                  |
| Average Case Resolution Time             | Average_Case_Resolution_Time_1                           | Service Dashboards Reports             | -                                                                                                                                                  |
| Average Case Resolution Time MTD         | Average_Case_Resolution_Time_MTD                         | Service Dashboards Reports             | -                                                                                                                                                  |
| Avg Case Resolution Time MTD by Agen     | Avg_Case_Resolution_Time_MTD_by_Agen                     | Service Dashboards Reports             | -                                                                                                                                                  |
| Case Resolution Time MTD by Origin       | Case_Resolution_Time_MTD_by_Origin                       | Service Dashboards Reports             | -                                                                                                                                                  |
| Cases Closed MTD                         | Cases_Closed_MTD                                         | Service Dashboards Reports             | -                                                                                                                                                  |
| Cases Closed MTD by Agent                | Cases_Closed_MTD_by_Agent                                | Service Dashboards Reports             | -                                                                                                                                                  |
| Cases Created MTD                        | Cases_Created_MTD                                        | Service Dashboards Reports             | -                                                                                                                                                  |
| Cases Currently Open                     | Cases_Currently_Open                                     | Service Dashboards Reports             | -                                                                                                                                                  |
| Cases Currently Open by Account          | Cases_Currently_Open_by_Account                          | Service Dashboards Reports             | -                                                                                                                                                  |
| Cases Currently Open by Agent            | Cases_Currently_Open_by_Agent                            | Service Dashboards Reports             | -                                                                                                                                                  |
| Cases Currently Open by Origin           | Cases_Currently_Open_by_Origin                           | Service Dashboards Reports             | -                                                                                                                                                  |
| Cases Currently Open by Priority         | Cases_Currently_Open_by_Priority                         | Service Dashboards Reports             | -                                                                                                                                                  |
| Cases Currently Open by Type             | Cases_Currently_Open_by_Type                             | Service Dashboards Reports             | -                                                                                                                                                  |
| Cases by Origin                          | Cases_by_Origin                                          | Service Dashboards Reports             | -                                                                                                                                                  |
| Cases by Origin and Open Status          | Cases_by_Origin_and_Open_Status                          | Service Dashboards Reports             | -                                                                                                                                                  |
| Cases by Priority                        | Cases_by_Priority                                        | Service Dashboards Reports             | -                                                                                                                                                  |
| Cases by Type and Open Status            | Cases_by_Type_and_Open_Status                            | Service Dashboards Reports             | -                                                                                                                                                  |
| Top 10 Cases by Age                      | Top_10_Cases_by_Age                                      | Service Dashboards Reports             | -                                                                                                                                                  |
| High Priority Open Cases by Account      | High_Priority_Open_Cases_by_Account                      | Service Dashboards Reports             | -                                                                                                                                                  |
| Trend of Case Resolution Time            | Trend_of_Case_Resolution_Time                            | Service Dashboards Reports             | -                                                                                                                                                  |
| Trend of Cases Closed                    | Trend_of_Cases_Closed                                    | Service Dashboards Reports             | -                                                                                                                                                  |
| Trend of Cases Created                   | Trend_of_Cases_Created                                   | Service Dashboards Reports             | Case creation trend                                                                                                                                |
| Sales Manager Activities                 | UsageActivitiesCompleted                                 | Dashboard Reports - Adoption           | Last 120 Days                                                                                                                                      |
| Activities by Salesperson                | Activities_by_Salesperson                                | Sales and Marketing Reports            | -                                                                                                                                                  |
| Marketing Exec Campaign ROI by Camp Type | CampaignROIbyCampaignType                                | Sales and Marketing Reports            | -                                                                                                                                                  |
| Marketing Exec Campaigns by ROI          | CampaignsbyROI                                           | Sales and Marketing Reports            | -                                                                                                                                                  |
| Sales Manager Leader Board               | Closed_Deals_leader_board                                | Sales and Marketing Reports            | -                                                                                                                                                  |
| Sales Manager Top Closed Deals           | Closed_opportunity                                       | Sales and Marketing Reports            | -                                                                                                                                                  |
| Marketing Exec Leads by Industry         | Leads_by_Industry                                        | Sales and Marketing Reports            | -                                                                                                                                                  |
| Marketing Exec Amount per Camp           | Marketing_Exec_Amount_per_Camp                           | Sales and Marketing Reports            | Average amount per campaign                                                                                                                        |
| Marketing Exec Conversion Rate           | Marketing_Exec_Conversion_Rate                           | Sales and Marketing Reports            | -                                                                                                                                                  |
| Marketing Exec Converted Amount          | Marketing_Exec_Converted_Amount                          | Sales and Marketing Reports            | -                                                                                                                                                  |
| Marketing Exec Converted and Won Amount  | Marketing_Exec_Converted_and_Won_Amount                  | Sales and Marketing Reports            | -                                                                                                                                                  |
| Marketing Exec Converted by Month        | Marketing_Exec_Converted_by_Month                        | Sales and Marketing Reports            | -                                                                                                                                                  |
| Marketing Exec Lead Trends by Status     | Marketing_Exec_Lead_Trends_by_Status                     | Sales and Marketing Reports            | -                                                                                                                                                  |
| Marketing Exec Leads Converted           | Marketing_Exec_Leads_Converted                           | Sales and Marketing Reports            | -                                                                                                                                                  |
| Marketing Exec Leads by Campaigns        | Marketing_Exec_Leads_by_Campaigns                        | Sales and Marketing Reports            | -                                                                                                                                                  |
| Marketing Exec # of Leads                | Marketing_Exec_of_Leads                                  | Sales and Marketing Reports            | -                                                                                                                                                  |
| Sales Exec Opportunity Product Pipeline  | OpportunityProductPipeline                               | Sales and Marketing Reports            | -                                                                                                                                                  |
| Sales Person Current Month Open Pipeline | SP_Current_Month_Open_Pipeline                           | Sales and Marketing Reports            | -                                                                                                                                                  |
| Sales Exec Closed Deals by Owner         | Sales_Exec                                               | Sales and Marketing Reports            | -                                                                                                                                                  |
| Sales Exec Bookings Trend                | Sales_Exec_Bookings_Trend                                | Sales and Marketing Reports            | -                                                                                                                                                  |
| Sales Exec Closed Deals QTD              | Sales_Exec_Closed_Deals_QTD                              | Sales and Marketing Reports            | -                                                                                                                                                  |
| Sales Exec Lost Deals                    | Sales_Exec_Lost_Deals                                    | Sales and Marketing Reports            | -                                                                                                                                                  |
| Sales Exec Open Deals                    | Sales_Exec_Open_Deals                                    | Sales and Marketing Reports            | -                                                                                                                                                  |
| Sales Exec Open Pipeline next 90 days    | Sales_Exec_Open_Pipeline_next_90_days                    | Sales and Marketing Reports            | -                                                                                                                                                  |
| Sales Exec Top Closed Deals              | Sales_Exec_Top_Closed_Deals                              | Sales and Marketing Reports            | -                                                                                                                                                  |
| Sales Manager Open Opportunities         | Sales_Manager_Open_Opportunities                         | Sales and Marketing Reports            | -                                                                                                                                                  |
| Sales Manager Open Pipeline              | Sales_Manager_Open_Pipeline                              | Sales and Marketing Reports            | -                                                                                                                                                  |
| Sales Manager Pipeline Next 90 days      | Sales_Manager_Pipeline_Next_90_days                      | Sales and Marketing Reports            | -                                                                                                                                                  |
| Sales Person All Activities              | Sales_Person_Activities_Completed                        | Sales and Marketing Reports            | -                                                                                                                                                  |
| Sales Person MTD Sales                   | Sales_Person_MTD_Sales                                   | Sales and Marketing Reports            | Month to Date sales                                                                                                                                |
| Sales Person Open Pipeline by stage      | Sales_Person_Open_Pipeline_by_stage                      | Sales and Marketing Reports            | -                                                                                                                                                  |
| Sample Report: Closed Sales              | SampleReportClosedSales                                  | Relatórios públicos                    | How much business have I closed so far?                                                                                                            |
| Sample Report: Sales Pipeline by Stage   | SampleReportSalesPipelinebyStage                         | Relatórios públicos                    | How much pipeline is at each sales stage?                                                                                                          |
| Sample Report: Open Cases By Priority    | SampleReportOpenCasesByPriority                          | Relatórios públicos                    | How many open support cases do we have by priority?                                                                                                |
| Sample Report: Open Deals                | SampleReportOpenDeals                                    | Relatórios públicos                    | What deals have not closed yet?                                                                                                                    |
| Sample Report: Pipeline By Close Month   | SampleReportPipelineByCloseMonth                         | Relatórios públicos                    | What pipeline do I have by close month?                                                                                                            |
| Sample Report: Leads by Lead Source      | SampleReportLeadsbyLeadSource                            | Relatórios públicos                    | How many leads has each lead source generated for me?                                                                                              |
| Sample Report: Top Accounts              | SampleReportTopAccounts                                  | Relatórios públicos                    | Which accounts are generating the most sales opportunities?                                                                                        |
| Sample Report: Cases Status by Rep       | SampleReportCasesStatusbyRep                             | Relatórios públicos                    | Who has the most open cases?                                                                                                                       |
| Sample Report: Solutions Added           | SampleReportSolutionsAdded                               | Relatórios públicos                    | How Many Solutions are Being Added to the Knowledgebase each Month?                                                                                |
| Sample Report: Sales Leaderboard         | SampleReportSalesLeaderboard                             | Relatórios públicos                    | Who are my top sales reps?                                                                                                                         |
| Sample Reports: Leads by Status          | SampleReportsLeadsbyStatus                               | Relatórios públicos                    | What is the status of leads created this quarter?                                                                                                  |
| Sample Report: Month to Date Trending    | SampleReportMonthtoDateTrending                          | Relatórios públicos                    | How do sales this month correlate to prior months?                                                                                                 |
| Sample Report: Pipeline History          | SampleReportPipelineHistory                              | Relatórios públicos                    | What did the pipeline look like as of...                                                                                                           |
| Sample Report: # of Documents            | SampleReportofDocuments                                  | Relatórios públicos                    | How many documents have been added to Salesforce?                                                                                                  |
| Sample Report: # of Reports              | SampleReportofReports                                    | Relatórios públicos                    | How many custom reports have we added to Salesforce?                                                                                               |
| Sample Report: Login Wall of Shame       | SampleReportLoginWallofShame                             | Relatórios públicos                    | Who is not logging in?                                                                                                                             |
| Sample Report: # of Cases                | SampleReportofCases                                      | Relatórios públicos                    | How many cases have been added to Salesforce?                                                                                                      |
| Sample Report: # of Contacts             | SampleReportofContacts                                   | Relatórios públicos                    | How many contacts do we have in Salesforce?                                                                                                        |
| Sample Report: # of Solutions            | SampleReportofSolutions                                  | Relatórios públicos                    | How many solutions have been added to Salesforce?                                                                                                  |
| Sample Report: # of Leads                | SampleReportofLeads                                      | Relatórios públicos                    | How many leads have we added to Salesforce?                                                                                                        |
| Sample Report: Active Users              | SampleReportActiveUsers                                  | Relatórios públicos                    | Who are my active users?                                                                                                                           |
| Sample Report: # of Tasks and Activities | SampleReportofTasksandActivities                         | Relatórios públicos                    | How many tasks and activies are being added to Salesforce?                                                                                         |
| Sample Report: Last Modified By          | SampleReportLastModifiedBy                               | Relatórios públicos                    | Who is tweaking custom reports?                                                                                                                    |
| Sample Report: # of Opportunities        | SampleReportofOpportunities                              | Relatórios públicos                    | How many opportunities are being added to Salesforce?                                                                                              |
| Sample Report: Custom Reports by User    | SampleReportCustomReportsbyUser                          | Relatórios públicos                    | Who is creating custom reports?                                                                                                                    |
| Sample Report: # of Open Tasks           | SampleReportofOpenTasks                                  | Relatórios públicos                    | How many open tasks do each of my users have?                                                                                                      |
| Sample Report: Login Leaderboard         | SampleReportLoginLeaderboard                             | Relatórios públicos                    | Who is logging in the most?                                                                                                                        |
| Sample Report: Users Logged In           | SampleReportUsersLoggedIn                                | Relatórios públicos                    | Which of my users are logging?                                                                                                                     |
| Sample Report: Completed Activities      | SampleReportCompletedActivities                          | Relatórios públicos                    | How many activities are my users completing?                                                                                                       |
| Sample Report: # of Accounts             | SampleReportofAccounts                                   | Relatórios públicos                    | How many accounts are being added to Salesforce?                                                                                                   |
| Sample Report: Document Library          | SampleReportDocumentLibrary                              | Relatórios públicos                    | What documents are in the document library?                                                                                                        |
| Opportunity Amount by Stage (Sample)     | Opportunity_Amount_by_Stage_Sample                       | Relatórios públicos                    | This report is used to power the embedded chart on the Accounts page.  Any changes made here will be reflected in that chart.                      |
| Sales Manager Closed Deals               | Sales_Manager_Closed_Deals                               | Sales and Marketing Reports            | -                                                                                                                                                  |
| Pipeline Report This Q                   | Pipeline_Report_This_Q                                   | Sales & Marketing Dashboards Reports   | -                                                                                                                                                  |
| Closed Won This Q by Type                | Closed_Won_This_Q_by_Type                                | Sales & Marketing Dashboards Reports   | -                                                                                                                                                  |
| Closed Won + ≥80% This Q by Owner        | Closed_Won_80_This_Q_by_Owner                            | Sales & Marketing Dashboards Reports   | -                                                                                                                                                  |
| Closed Lost by Reason                    | Closed_Lost_by_Reason                                    | Sales & Marketing Dashboards Reports   | -                                                                                                                                                  |
| Open Oppties This Q - No Acti Last 96hrs | Open_Oppties_This_Q_No_Acti_Last_96hrs                   | Sales & Marketing Dashboards Reports   | -                                                                                                                                                  |
| Closed Won This Q by Owner               | Closed_Won_This_Q_by_Owner                               | Sales & Marketing Dashboards Reports   | -                                                                                                                                                  |
| Open Oppties This Q                      | Open_Oppties_This_Q                                      | Sales & Marketing Dashboards Reports   | -                                                                                                                                                  |
| Win Ratio                                | Win_Ratio                                                | Sales & Marketing Dashboards Reports   | -                                                                                                                                                  |
| Closed Won by Type                       | Closed_Won_by_Type                                       | Sales & Marketing Dashboards Reports   | -                                                                                                                                                  |
| Leads Converted All Time                 | Leads_Converted_All_Time                                 | Sales & Marketing Dashboards Reports   | -                                                                                                                                                  |
| Leads Converted by FQ                    | Leads_Converted_by_FQ                                    | Sales & Marketing Dashboards Reports   | -                                                                                                                                                  |
| Leads Created Current FQ                 | Leads_Created_Current_FQ                                 | Sales & Marketing Dashboards Reports   | -                                                                                                                                                  |
| Leads Converted Current FQ               | Leads_Converted_Current_FQ2                              | Sales & Marketing Dashboards Reports   | -                                                                                                                                                  |
| Conversion Rate                          | Conversion_Rate                                          | Sales & Marketing Dashboards Reports   | -                                                                                                                                                  |
| Hot Leads w/o Activity >96 Hours         | Hot_Leads_w_o_Activity_96_Hours                          | Sales & Marketing Dashboards Reports   | -                                                                                                                                                  |
| Sample Flow Report: Screen Flows         | flow_screen_prebuilt_report                              | Relatórios públicos                    | Which flows run, what’s the status of each interview, and how long do users take to complete the screens?                                          |
| Cadence  Completion Reason Report        | CRM_180925_Cadence_Completion_Report                     | Sample Sales Reports                   | Which cadence is the most effective for lead converts or completion?                                                                               |
| Lead Conversion Report                   | CRM_180925_Lead_Conversion_Report                        | Sample Sales Reports                   | How many leads are my sales reps converting? What’s the dollar value? Who’s the top performer?                                                     |
| Call Activity Report                     | CRM_180925_Call_Activity_Report                          | Sample Sales Reports                   | How many calls are my sales reps making? Who’s the top performer?                                                                                  |
| Cadence Engagement Report                | CRM_180925_Cadence_Engagement_Report                     | Sample Sales Reports                   | Which cadence results in the best target engagement? Which specific steps?                                                                         |
| Cadence Steps with Monthly Metrics Repor | CRM_180925_Cadence_Engagement_Monthly_Metric_Report      | Sample Sales Reports                   | Which Cadence results in the best target engagement per month? Which specific steps, email templates, and call scripts?                            |
| Leads  with Monthly Engagements Report   | CRM_180925_Lead_Monthly_Metric_Report                    | Sample Sales Reports                   | How engaged are my leads on overall email and call activity per month?                                                                             |
| Leads with Daily Engagements Report      | CRM_180925_Lead_Daily_Metric_Report                      | Sample Sales Reports                   | How engaged are my leads on overall email and call activity per day?                                                                               |
| Contacts with Monthly Engagements Report | CRM_180925_Contact_Monthly_Metric_Report                 | Sample Sales Reports                   | How engaged are my contacts on overall email and call activity per month?                                                                          |
| Contacts with Daily Engagements Report   | CRM_180925_Contact_Daily_Metric_Report                   | Sample Sales Reports                   | How engaged are my contacts on overall email and call activity per day?                                                                            |
| Users with Monthly Engagements Report    | CRM_180925_User_Monthly_Metric_Report                    | Sample Sales Reports                   | How engaged are my users on overall email and call activity per month?                                                                             |
| Users with Daily Engagements Report      | CRM_180925_User_Daily_Metric_Report                      | Sample Sales Reports                   | How engaged are my users on overall email and call activity per day?                                                                               |
| Cadences and Completed Trackers          | CRM_180925_Complete_Sales_Candences_amp_Trackers_Report  | Sales Engagement Dashboard Reports     | How many targets is each sales rep taking to completion, and with what dispositions?                                                               |
| Contact Engagement by Account            | CRM_180925_Contacts_Engagement_grouped_by_account_Report | Sales Engagement Dashboard Reports     | How engaged are my contacts on email and call activity per day?                                                                                    |
| Engagement by Sales Rep and Month        | CRM_180925_Grouped_Users_Monthly_Report                  | Sales Engagement Dashboard Reports     | How engaged are my users on overall email and call activity per month?                                                                             |
| Leads with Engagements by Day            | CRM_180925_Lead_Daily_Engagement_Report                  | Sales Engagement Dashboard Reports     | How engaged are my leads on overall email and call activity per day?                                                                               |
| Users with Engagements by Day            | CRM_180925_User_Daily_Engagement_Report                  | Sales Engagement Dashboard Reports     | How engaged are my users on overall email and call activity per day?                                                                               |
| Cadence and Step Engagement              | CRM_180925_Sales_Cadence_Steps_Monthly_Metrics_Report    | Sales Engagement Dashboard Reports     | Which cadences and steps generate the most engagement?                                                                                             |
| Call Script Engagement by Month          | CRM_180925_CallScript_Monthly_Metrics_Report             | Sales Engagement Dashboard Reports     | Which call scripts generate the most engagement?                                                                                                   |
| Email Template Engagement by Month       | CRM_180925_EmailTemplate_Monthly_Metrics_Report          | Sales Engagement Dashboard Reports     | Which email templates generate the most engagement?                                                                                                |
| Leads Converted by Sales Rep             | CRM_180925_Leads_Converted_by_Sales_Rep_Report           | Sales Engagement Dashboard Reports     | Which reps have converted the most leads in the last 30 days with each cadence?                                                                    |
| Lead Conversions by Cadence              | CRM_180925_Lead_Cadence_Tracker_Conversion_Report        | Sales Engagement Dashboard Reports     | Which leads have converted in the last 30 days for each cadence? (Also includes leads not in cadences.)                                            |
| Leads with Cadence Trackers              | CRM_180925_Leads_with_Sales_Cadence_Trackers_Report      | Sales Engagement Dashboard Reports     | Which leads are in cadences?                                                                                                                       |
| Contacts with Cadence Trackers           | CRM_180925_Contacts_with_Sales_Cadence_Trackers_Report   | Sales Engagement Dashboard Reports     | Which contacts are in cadences?                                                                                                                    |
| Opportunities with Activities this Month | Opportunities_with_Activities_this_Month                 | Activity Reports                       | -                                                                                                                                                  |
| Accounts with Activities                 | Accounts_with_Activities                                 | Activity Reports                       | -                                                                                                                                                  |
| Neglected Open Opportunities             | Opptys_Report                                            | Activity Reports                       | -                                                                                                                                                  |
| Sales Rep Activities                     | Sales_Rep_Activities                                     | Activity Reports                       | -                                                                                                                                                  |
| SR: Top Open Opportunities               | Top_Open_Opportunities_r6f                               | Getting Started - Sales Representative | -                                                                                                                                                  |
| Call Script Engagement Report            | CRM_180925_Call_Template_Report                          | Sample Sales Reports                   | Which call script results in the best target engagement?                                                                                           |
| Email Template Engagement Report         | CRM_180925_Email_Template_Report                         | Sample Sales Reports                   | Which email template results in the best target engagement?                                                                                        |
| Sample Report: Orchestration Runs        | flow_orchestration_run_ootb_report_two_four_eight        | Relatórios públicos                    | What orchestration runs have been created and what's the current status of each run?                                                               |
| Sample Report: Orchestration Stage Runs  | flow_orchestration_stage_run_ootb_report_two_four_eight  | Relatórios públicos                    | What orchestration stage runs have been created and what's the current status of each run?                                                         |
| Sample Report: Orchestration Step Runs   | flow_orchestration_step_run_ootb_report_two_four_eight   | Relatórios públicos                    | What orchestration step runs have been created and what's the current status of each run?                                                          |
| Sample Report: Orchestration Work Items  | flow_orchestration_work_item_ootb_report_two_four_eight  | Relatórios públicos                    | What orchestration work items were created and what's the current status of each work item?                                                        |
| Sample Report: Orchestration Run Logs    | flow_orchestration_log_ootb_report_two_four_eight        | Relatórios públicos                    | What orchestration run logs were created and what happened in their associated orchestration runs?                                                 |
| Emergencies                              | Emergencies                                              | Field Service Copilot Reports          | Shows today’s emergency appointments.                                                                                                              |
| In-jeopardy appointments                 | Injeopardy_Appointments                                  | Field Service Copilot Reports          | Shows today’s in-jeopardy appointments.                                                                                                            |
| Unscheduled appointments due today       | Unscheduled_Appointments                                 | Field Service Copilot Reports          | Shows unscheduled appointments that are due today.                                                                                                 |
| Weekly Workstream Util. and Availability | WorkStream_vs_Availability_Monthly_V1_zd1                | Field Service Work Capacity Reports    | Identify weekly consumption trends by comparing the workstream usage to the work capacity availability for a service territory or all territories. |
| Weekly Workstream Utilization and Limit  | WorkStream_vs_Capacity_Limit_Monthly_V1                  | Field Service Work Capacity Reports    | Identify weekly consumption trends by comparing the workstream usage per service territory to the work capacity limit.                             |
| Workstream Utilization and Work Capacity | WorkStream_vs_Capacity_Limit_V1                          | Field Service Work Capacity Reports    | Compare the total daily workstream utilization to the daily work capacity limit.                                                                   |
| Workstream Utilization and Availability  | WorkStream_vs_Overall_Availability_V1                    | Field Service Work Capacity Reports    | Compare the total daily workstream consumption to the daily work capacity availability.                                                            |
| Work Capacity Availability.V2            | Work_Capacity_Availability                               | Field Service Work Capacity Reports    | Ability to analyze and measure availability of my workforce by reviewing daily availability of all Service Territories                             |
| Work Capacity Availability by Territory  | Work_Capacity_Availability_by_Territory                  | Field Service Work Capacity Reports    | Ability to analyze and measure availability of my workforce by reviewing daily availability by Service Territory                                   |
| AC - relatório base 1                    | ACVisaoCiclo                                             | Gerenciamento de contas                | -                                                                                                                                                  |
| AC - relatório base 2 (somente fieis)    | AC_relatrio_base_2_gJu                                   | Gerenciamento de contas                | -                                                                                                                                                  |
| AC - relatório base (perdido e perdendo) | AC_relatrio_base_3_abr                                   | Gerenciamento de contas                | -                                                                                                                                                  |
| AC - relatório base 4 (ponto pedido)     | AC_relatrio_base_4_ZRK                                   | Gerenciamento de contas                | -                                                                                                                                                  |
| Contas negligenciadas                    | DW_ContasNegligenciadas                                  | Getting Started - Sales Manager        | -                                                                                                                                                  |
| Activities Logged on Opportunities       | Activities_with_Opportunities_all_time_cdR               | Trailhead                              | Use for tracking total activities logged on opportunities for all time.                                                                            |
| Assigned Badges By User                  | All_Badges_By_User_Assigned                              | Trailhead                              | Report on all assigned badges that are not in progress or completed to create a list of users to follow-up with.                                   |
| All Users by Badge In Progress           | All_Trailhead_Badges                                     | Trailhead                              | Report on all users by badges in progress.                                                                                                         |
| All Badges By User Completed             | All_Trailhead_Badges_By_User                             | Trailhead                              | Report on all badges earned by user                                                                                                                |
| All Badges By User Completed - this QTR  | All_Trailhead_Badges_By_User1                            | Trailhead                              | Report on all Trailhead badges earned by user this quarter.                                                                                        |
| All Badges By User Completed -  Prev QTR | All_Trailhead_Badges_By_User11                           | Trailhead                              | Use for tracking all badges earned by user for the previous quarter.                                                                               |
| Badges Completed By User - This Month    | All_Trailhead_Badges_By_User12                           | Trailhead                              | Use for tracking all badges earned by user in the last 30 days.                                                                                    |
| Archived Badges                          | Archived_Badge_Records                                   | Trailhead                              | Report on badges (e.g. modules, projects, superbadges) that have been retired by Trailhead (e.g. can no longer be earned by trailblazers).         |
| Archived Trails                          | Archived_Trails                                          | Trailhead                              | Report on trails that have been retired by Trailhead (e.g. can no longer be earned by trailblazers).                                               |
| Archived User Badges                     | Archived_User_Badges                                     | Trailhead                              | Report on user badges that have been retired by Trailhead (e.g. can no longer be earned by trailblazers).                                          |
| Assigned Trailmixes                      | Assigned_Trailmixes                                      | Trailhead                              | Use for tracking assigned trailmixes to all users.                                                                                                 |
| Assigned Trailmixes - By Status          | Assigned_Trailmixes1                                     | Trailhead                              | Use for tracking trailmix assignments by status.                                                                                                   |
| Due Trailmixes - Last 90 Days            | Assigned_Trailmixes11                                    | Trailhead                              | Use for tracking trailmixes that were due over the last 90 days.                                                                                   |
| Due Trailmixes - Next 7 Days             | Assigned_Trailmixes111                                   | Trailhead                              | Use for tracking trailmixes that are due in the next 7 days.                                                                                       |
| Due Trailmixes - Last 90 Days            | Assigned_Trailmixes1111                                  | Trailhead                              | Trailmixes due in the last 90 days                                                                                                                 |
| Trailmixes Created - Last 60 Days        | Assigned_Trailmixes1112                                  | Trailhead                              | Use for tracking trailmixes created in the last 60 days.                                                                                           |
| Trailmixes Created - All Time            | Assigned_Trailmixes11121                                 | Trailhead                              | Use for tracking trailmixes created for all time.                                                                                                  |
| Due Trailmixes - All Time                | Assigned_Trailmixes11122                                 | Trailhead                              | Use for tracking all due trailmixes.                                                                                                               |
| Badge Completion Duration                | Badge_Completion_Duration                                | Trailhead                              | Use to determine, on average, how long it takes to complete a badge.                                                                               |
| Badge Trend                              | Badge_Trend                                              | Trailhead                              | Report on the trend of badges awarded                                                                                                              |
| Badges Awarded This Week                 | Badges_Awarded_This_Week                                 | Trailhead                              | Report on badges earned by users this week.                                                                                                        |
| Completed Badges for User                | Completed_Badges_for_User                                | Trailhead                              | Report on all completed badges for a specific user.                                                                                                |
| Trailmixes Completed - All Time          | Completed_Trailmixes                                     | Trailhead                              | Use for tracking all trailmixes completed for all time.                                                                                            |
| Trailmixes Completed - Last 90 Days      | Completed_Trailmixes1                                    | Trailhead                              | Use for tracking trailmixes completed over the last 90 days.                                                                                       |
| Trailmixes Completed - All Time by User  | Completed_Trailmixes2                                    | Trailhead                              | Use for tracking trailmixes completed for all time by user.                                                                                        |
| Debug Logs                               | Debug_Logs                                               | Trailhead                              | Any debug messages written by the Trailhead app.                                                                                                   |
| Most Active Users                        | Most_Active_Users                                        | Trailhead                              | Report on users who have the most trailhead activity                                                                                               |
| Most Popular Badges                      | Most_Popular_Badges                                      | Trailhead                              | Report on the most popular badges earned by your users                                                                                             |
| New Badges Awarded This Month            | New_Badges_Awarded_This_Month                            | Trailhead                              | Report on badges earned by users this month.                                                                                                       |
| New Badges (Last 90 Days)                | New_Badges_Last_90_Days                                  | Trailhead                              | Use for discovering newly added badges in the last 90 days.                                                                                        |
| Open Opportunities - All Time            | New_Opportunities_Report_CEl1                            | Trailhead                              | Use for tracking all open opportunities for all time.                                                                                              |
| Closed Won Opportunities - All Time      | New_Opportunities_Report_CEl2                            | Trailhead                              | Use for tracking closed won opportunities in your pipeline.                                                                                        |
| New Trails (Last 90 Days)                | New_Trails_Last_90_Days                                  | Trailhead                              | Use for discovering newly added trails in the last 90 days.                                                                                        |
| Open Cases By Average Age                | Open_Cases_with_Avg_Age_bIm                              | Trailhead                              | Use for tracking the average number of days a case has been opened.                                                                                |
| Total Badges Assigned                    | Total_Badges_Assigned                                    | Trailhead                              | Use for tracking which badges have been assigned to users that haven't been started or completed                                                   |
| Total Badges Completed                   | Total_Badges_Completed                                   | Trailhead                              | Use for tracking total number of badges awarded by badge name.                                                                                     |
| Total Badges In Progress                 | Total_Badges_In_Progress                                 | Trailhead                              | Use to track how many badges have been started but not finished.                                                                                   |
| Total Case Activities - Open and Closed  | Total_Case_Activities_open_and_closed_CQn                | Trailhead                              | Use for tracking open and closed activities logged on cases.                                                                                       |
| Total Cases - Closed Status              | Total_Cases_closed_status_c8X                            | Trailhead                              | Use for tracking cases that have been closed.                                                                                                      |
| Total Cases - All Status                 | Total_Cases_closed_status_c8X1                           | Trailhead                              | Use for tracking all cases regardless of status.                                                                                                   |
| Total Cases - Open Status                | Total_Cases_closed_status_c8X2                           | Trailhead                              | Use for tracking open cases.                                                                                                                       |
| Trailhead Leaderboard                    | Trailhead_Leaderboard_vIP                                | Trailhead                              | View your Trailhead user's ranks, total points, and other key user data.                                                                           |
| Trailmix Assignments                     | Trailmix_Assignments                                     | Trailhead                              | What trailmixes are assigned to users that are not yet completed?                                                                                  |
| Weekly Workstream Util. and Availability | WorkStream_vs_Availability_Monthly_V2                    | Field Service Work Capacity Reports    | Identify weekly consumption trends by comparing the workstream usage to the work capacity availability for a service territory or all territories. |
| Weekly Workstream Utilization and Limit  | WorkStream_vs_Capacity_Limit_Monthly_V2                  | Field Service Work Capacity Reports    | Identify weekly consumption trends by comparing the workstream usage per service territory to the work capacity limit.                             |
| Workstream Utilization and Work Capacity | WorkStream_vs_Capacity_Limit_V2                          | Field Service Work Capacity Reports    | Compare the total daily workstream utilization to the daily work capacity limit.                                                                   |
| Workstream Utilization And Availability  | WorkStream_vs_Overall_Availability_V2                    | Field Service Work Capacity Reports    | Compare the total daily workstream consumption to the daily work capacity availability.                                                            |
| Casos                                    | Casos_A4v                                                | Relatórios privados                    | -                                                                                                                                                  |
| Oportunidades                            | Oportunidades_deD                                        | Relatórios privados                    | -                                                                                                                                                  |
| Ordens de trabalho                       | Ordens_de_trabalho_5EX                                   | Relatórios privados                    | -                                                                                                                                                  |
| Cópia de Ordens de trabalho              | Ordens_de_trabalho_5EX1                                  | Relatórios públicos                    | -                                                                                                                                                  |
| Cópia de Casos                           | Casos_A4v1                                               | Relatórios públicos                    | -                                                                                                                                                  |
| Cópia de Oportunidades                   | Oportunidades_deD1                                       | Relatórios públicos                    | -                                                                                                                                                  |
| Ativos                                   | Ativos_rgw                                               | Relatórios públicos                    | -                                                                                                                                                  |
| Ordens de trabalho                       | Ordens_de_trabalho_pCb                                   | Relatórios públicos                    | -                                                                                                                                                  |
| Compromissos de serviço                  | Compromissos_de_servio_I1F                               | Relatórios públicos                    | -                                                                                                                                                  |
| Compromissos de serviço 2                | Compromissos_de_servio_2_GzT                             | Relatórios públicos                    | -                                                                                                                                                  |
| Ordens de trabalho 2                     | Ordens_de_trabalho_2_uUa                                 | Relatórios públicos                    | -                                                                                                                                                  |
| Contas com conta pai                     | Contas_com_conta_pai_9He                                 | Relatórios privados                    | -                                                                                                                                                  |
| Contas com Ativos                        | Contas_com_Ativos_3QT                                    | Relatórios privados                    | -                                                                                                                                                  |
| Habilidades de recursos de serviços      | Habilidades_de_recursos_de_servios_Hwu                   | Field Service Reports                  | -                                                                                                                                                  |
| Análise de margem 01                     | Anlise_de_margem_01_POq                                  | Sales and Marketing Reports            | -                                                                                                                                                  |
| Análise de margem 02                     | Anlise_de_margem_02_4Rx                                  | Sales and Marketing Reports            | -                                                                                                                                                  |
| Análise de margem 03                     | Anlise_de_margem_03_HpQ                                  | Sales and Marketing Reports            | -                                                                                                                                                  |
| Qtd. por versão de cálculo               | QtdPorVersaoCalculo                                      | Setup do NPX                           | -                                                                                                                                                  |
| Catálogos e produtos                     | CatalogosProdutyos                                       | Setup do NPX                           | -                                                                                                                                                  |

# Permission Sets

| Rótulo                                                   | Nome de API                            | Descrição                                                                                                                                                                                                                                                     |
| -------------------------------------------------------- | -------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 00eHZ000007aGDVYA2                                       | X00eHZ000007aGDVYA2                    | -                                                                                                                                                                                                                                                             |
| 00eHZ000007aGDWYA2                                       | X00eHZ000007aGDWYA2                    | -                                                                                                                                                                                                                                                             |
| 00eHZ000007aGDXYA2                                       | X00eHZ000007aGDXYA2                    | -                                                                                                                                                                                                                                                             |
| 00eHZ000007aH37YAE                                       | X00eHZ000007aH37YAE                    | -                                                                                                                                                                                                                                                             |
| 00eHZ000007aH38YAE                                       | X00eHZ000007aH38YAE                    | -                                                                                                                                                                                                                                                             |
| Field Service AI Agent Permissions                       | FSL_AIAgent_Permissions                | -                                                                                                                                                                                                                                                             |
| Field Service AI Agent License                           | FSL_AIAgent_License                    | -                                                                                                                                                                                                                                                             |
| 00eHZ000007aoThYAI                                       | X00eHZ000007aoThYAI                    | -                                                                                                                                                                                                                                                             |
| ScaleCenterUsers                                         | ScaleCenterUsers                       | -                                                                                                                                                                                                                                                             |
| Usuário de integração do Slack                           | sfdc_slack                             | Permite que o usuário de integração acesse objetos usados no Slack.                                                                                                                                                                                           |
| sfdc.activityplatform                                    | sfdc_activityplatform                  | Permset for the 'sfdc.activityplatform' C2C integration                                                                                                                                                                                                       |
| 00ex00000018ozW_128_09_43_34_4                           | X00ex00000018ozW_128_09_43_34_4        | -                                                                                                                                                                                                                                                             |
| 00e3i000000Qpg4AAC                                       | X00e3i000000Qpg4AAC                    | -                                                                                                                                                                                                                                                             |
| 00e3i000000Qrm9AAC                                       | X00e3i000000Qrm9AAC                    | -                                                                                                                                                                                                                                                             |
| 00eHn000001mn7BIAQ                                       | X00eHn000001mn7BIAQ                    | -                                                                                                                                                                                                                                                             |
| Sales User                                               | Sales_User                             | -                                                                                                                                                                                                                                                             |
| 00eas000000Pt7lAAC                                       | X00eas000000Pt7lAAC                    | -                                                                                                                                                                                                                                                             |
| DW | NOX | Full                                          | DW_NOX                                 | Conjunto de permissões que concede acesso completo para todos os objetos e campos do NOX.                                                                                                                                                                     |
| DW | NOX | Core                                          | DW_NOX_Core                            | Conjunto de permissões que permite a utilização dos recursos básicos do NOX, como acesso à classes controladoras, configurações personalizadas, etc.                                                                                                          |
| DW | NOX | RO                                            | DW_NOX_RO                              | Conjunto de permissões que permite somente leitura do objetos e campos do NOX.                                                                                                                                                                                |
| DW | NOX | Full Group                                    | DW_NOX_FullGroup                       | -                                                                                                                                                                                                                                                             |
| DW | NOX | RO Group                                      | DW_NOX_ROGroup                         | -                                                                                                                                                                                                                                                             |
| DW AC                                                    | AC                                     | -                                                                                                                                                                                                                                                             |
| DW - SPT - User access                                   | DWSPTUserAccess                        | -                                                                                                                                                                                                                                                             |
| Criador de modelo de e-mail LEX                          | Criador_de_modelo_de_e_mail_LEX        | -                                                                                                                                                                                                                                                             |
| Lightning Map Admin                                      | Lightning_Map_Admin                    | Grants users access to the Map Error object, showing queries and inaccessible fields when users face issues viewing the recordMap component                                                                                                                   |
| Field Service Integration                                | sfdc_fieldservice                      | Permissions to access data needed for optimization, automatic scheduling, and service appointment bundling.(Licenseless)                                                                                                                                      |
| Field Service Dispatcher Permissions                     | FSL_Dispatcher_Permissions             | -                                                                                                                                                                                                                                                             |
| Field Service Dispatcher License                         | FSL_Dispatcher_License                 | -                                                                                                                                                                                                                                                             |
| Field Service Resource Permissions                       | FSL_Resource_Permissions               | -                                                                                                                                                                                                                                                             |
| Field Service Resource License                           | FSL_Resource_License                   | -                                                                                                                                                                                                                                                             |
| Field Service Mobile License                             | FSL_Mobile_License                     | -                                                                                                                                                                                                                                                             |
| Field Service Agent Permissions                          | FSL_Agent_Permissions                  | -                                                                                                                                                                                                                                                             |
| Field Service Agent License                              | FSL_Agent_License                      | -                                                                                                                                                                                                                                                             |
| Field Service Self Service Permissions                   | FSL_Community_Self_Service_Permissions | -                                                                                                                                                                                                                                                             |
| Field Service Guest User Permissions                     | FSL_Guest_User_Permissions             | -                                                                                                                                                                                                                                                             |
| Field Service Community Dispatcher Permissions           | FSL_Community_Dispatcher_Permissions   | -                                                                                                                                                                                                                                                             |
| Field Service Community Dispatcher License               | FSL_Community_Dispatcher_License       | -                                                                                                                                                                                                                                                             |
| Field Service Admin Permissions                          | FSL_Admin_Permissions                  | -                                                                                                                                                                                                                                                             |
| Field Service Admin License                              | FSL_Admin_License                      | -                                                                                                                                                                                                                                                             |
| 00eas000000TXi9AAG                                       | X00eas000000TXi9AAG                    | -                                                                                                                                                                                                                                                             |
| DW - Cotação de frete                                    | DWCotacaoFretePermissionSet            | -                                                                                                                                                                                                                                                             |
| DW Plug and Play - Catálogo de preço e itens do catálogo | DWPNPCatalogoPrecoItensCatalogo        | -                                                                                                                                                                                                                                                             |
| DW - Plug and play - Aplicativos                         | DWPlugAndPlayAplicativos               | -                                                                                                                                                                                                                                                             |
| DW Plug and Play Ativo                                   | DWPlugAndPlayAtivo                     | -                                                                                                                                                                                                                                                             |
| DW Plug and Play - Campanha                              | DWPlugAndPlayCampanha                  | -                                                                                                                                                                                                                                                             |
| DW - Plug and Play - Casos                               | DWPlugAndPlayCasos                     | -                                                                                                                                                                                                                                                             |
| DW Plug and Play Compromisso                             | DWPlugAndPlayCompromisso               | -                                                                                                                                                                                                                                                             |
| DW Plug and Play Condição de pagamento                   | DWPlugAndPlayCondicaoPagamento         | -                                                                                                                                                                                                                                                             |
| DW Plug and Play - Conta                                 | DWPlugAndPlayConta                     | -                                                                                                                                                                                                                                                             |
| DW Plug and Play - Contato                               | DWPlugAndPlayContato                   | -                                                                                                                                                                                                                                                             |
| DW Plug and Play Contrato                                | DWPlugAndPlayContrato                  | -                                                                                                                                                                                                                                                             |
| DW Plug and Play - Cotação                               | DWPlugAndPlayCotacao                   | -                                                                                                                                                                                                                                                             |
| DW Plug and Play - Item de linha da cotação              | DWPlugAndPlayItemLinhaCotacao          | -                                                                                                                                                                                                                                                             |
| DW Plug and Play - Lead                                  | DWPlugAndPlayLead                      | -                                                                                                                                                                                                                                                             |
| DW Plug and Play - Notas fiscais e itens                 | DWPlugAndPlayNotasFiscais              | -                                                                                                                                                                                                                                                             |
| DW Plug and Play - Pedido                                | DWPlugAndPlayPedido                    | -                                                                                                                                                                                                                                                             |
| DW Plug and Play - Produto                               | DWPlugAndPlayProduto                   | -                                                                                                                                                                                                                                                             |
| DW - Plug and Play - Produto da Oportunidade             | DWPlugAndPlayProdutoOportunidade       | -                                                                                                                                                                                                                                                             |
| DW Plug and Play - Produto do pedido                     | DWPlugAndPlayProdutoPedido             | -                                                                                                                                                                                                                                                             |
| DW - Plug and play - recomendações                       | DWPlugAndPlayRecomendacoes             | -                                                                                                                                                                                                                                                             |
| DW Plug and Play - Tarefa                                | DWPlugAndPlayTarefa                    | -                                                                                                                                                                                                                                                             |
| DW Plug and Play - Títulos                               | DWPlugAndPlayTitulos                   | -                                                                                                                                                                                                                                                             |
| DW Plug and Play Usuário                                 | DWPlugAndPlayUsuario                   | -                                                                                                                                                                                                                                                             |
| DW Plug and Play Entrada da tabela de preços             | DWPlugPlayEntradaTabelaPrecos          | -                                                                                                                                                                                                                                                             |
| DW - Curva ABC de conta                                  | DW_Curva_ABC_de_conta                  | -                                                                                                                                                                                                                                                             |
| DW - Endereço pré-definido                               | DW_Endereco_pre_definido               | -                                                                                                                                                                                                                                                             |
| DW - Fatores de precificação                             | DW_FatoresPrecificacao                 | -                                                                                                                                                                                                                                                             |
| Daspe Web - Plug and play                                | DW_PlugAndPlay                         | -                                                                                                                                                                                                                                                             |
| DW - Plug and play - Oportunidade                        | DW_Plug_and_play_oportunidade          | -                                                                                                                                                                                                                                                             |
| DW - Resumo Financeiro                                   | DW_Resumo_Financeiro                   | -                                                                                                                                                                                                                                                             |
| DW Sintegra                                              | DW_Sintegra                            | -                                                                                                                                                                                                                                                             |
| DW - VIA CEP                                             | DW_VIA_CEP                             | -                                                                                                                                                                                                                                                             |
| Document Manager - Admin                                 | Document_Manager_Admin                 | -                                                                                                                                                                                                                                                             |
| Daspe Web - Plug And Play - Grupo de permissões          | DWPlugAndPlayGrupoPermissao            | -                                                                                                                                                                                                                                                             |
| Trailhead Admin                                          | Th_Badge_Admin                         | Add this permission set to administer the Trailhead badge package. This includes assigning badges as well as scheduling the Trailhead sync. Requires non-packagable report, dashboard, and customize application user permissions via another permission set. |
| Trailhead Assigner                                       | Th_Badge_Assigner                      | Add this permission set to users who need to assign badges as part of their enablement duties. This includes assigning badges as well as reporting on badges. Requires non-packagable report and dashboard user permissions via another permission set.       |
| Trailhead User                                           | Th_Badge_User                          | Add this permission set to any internal users who needs to run reports on the Trailhead badges earned by users within the org. Requires non-packagable report and dashboard user permissions via another permission set or profile.                           |
| 00eas000000l1rtAAA                                       | X00eas000000l1rtAAA                    | -                                                                                                                                                                                                                                                             |
| 00eas000000l1tVAAQ                                       | X00eas000000l1tVAAQ                    | -                                                                                                                                                                                                                                                             |
| 00eas000000l1v7AAA                                       | X00eas000000l1v7AAA                    | -                                                                                                                                                                                                                                                             |
| 00eas000000l1wjAAA                                       | X00eas000000l1wjAAA                    | -                                                                                                                                                                                                                                                             |
| 00eas000000l1yLAAQ                                       | X00eas000000l1yLAAQ                    | -                                                                                                                                                                                                                                                             |
| 00eas000000l1zxAAA                                       | X00eas000000l1zxAAA                    | -                                                                                                                                                                                                                                                             |
| Plano de contas - admin                                  | Plano_de_contas_admin                  | -                                                                                                                                                                                                                                                             |
| 00eas000000rKtRAAU                                       | X00eas000000rKtRAAU                    | -                                                                                                                                                                                                                                                             |
| 00eas000000rL7xAAE                                       | X00eas000000rL7xAAE                    | -                                                                                                                                                                                                                                                             |
| Arquivos                                                 | Arquivos                               | -                                                                                                                                                                                                                                                             |
| integracao                                               | integracao                             | -                                                                                                                                                                                                                                                             |
| acesso objeto                                            | acesso_objeto                          | -                                                                                                                                                                                                                                                             |
| Visão geral das unidades de negócio                      | DWVisaoGeralUnidadesNegocio            | Conjunto de permissões utilizado para que os usuários intermediários e backoffice visualizem a carteira de clientes, ativos e ordens de trabalho de ambas as unidades de negócio (Mercadão e Agrolíder)                                                       |
| Knowledge LSF Permission Set                             | Knowledge_LSF_Permission_Set           | Grants CRUD permission for Knowledge, as well as Knowledge user permissions.                                                                                                                                                                                  |
| DW NPX | Admin                                           | Admin                                  | -                                                                                                                                                                                                                                                             |
| DW NPX | User                                            | User                                   | -                                                                                                                                                                                                                                                             |

# Páginas Visualforce

| Nome                                   | Nome de API                            | Versão da API | Descrição                                                                                           |
| -------------------------------------- | -------------------------------------- | ------------- | --------------------------------------------------------------------------------------------------- |
| Log_integraca_formatar_Response        | Log_integraca_formatar_Response        | 64            | -                                                                                                   |
| Log_integracao_formatar                | Log_integracao_formatar                | 64            | -                                                                                                   |
| DWPropostaPersonalizadaOppAtivo        | DWPropostaPersonalizadaOppAtivo        | 63            | -                                                                                                   |
| Relatório Consolidado OT               | RelatorioConsolidadoOT                 | 63            | -                                                                                                   |
| Proposta personalizada - Mercadão      | DWPropostaPersonalizadaOppMercadao     | 61            | -                                                                                                   |
| Romaneio                               | DWRomaneio                             | 65            | -                                                                                                   |
| Romaneio (CRM)                         | DWRomaneioCRM                          | 65            | -                                                                                                   |
| Romaneio de devolução (CRM)            | DWRomaneioDevolucaoCRM                 | 65            | -                                                                                                   |
| SiteRegister                           | SiteRegister                           | 62            | Página padrão Registro de usuário dos sites do Salesforce                                           |
| ChangePassword                         | ChangePassword                         | 62            | Página padrão Alteração de senha dos sites do Salesforce                                            |
| ForgotPassword                         | ForgotPassword                         | 62            | Página padrão Confirmação de esquecimento de senha dos sites do Salesforce                          |
| SiteLogin                              | SiteLogin                              | 62            | Página padrão Login nos sites do Salesforce                                                         |
| ForgotPasswordConfirm                  | ForgotPasswordConfirm                  | 62            | Página padrão Confirmação de esquecimento de senha dos sites do Salesforce                          |
| SiteRegisterConfirm                    | SiteRegisterConfirm                    | 62            | Página padrão Confirmação de registro do usuário dos sites do Salesforce                            |
| MyProfilePage                          | MyProfilePage                          | 62            | Página padrão Meu perfil dos sites do Salesforce                                                    |
| StdExceptionTemplate                   | StdExceptionTemplate                   | 62            | Modelo padrão do Lightning Platform para páginas de exceção padrão                                  |
| SiteTemplate                           | SiteTemplate                           | 62            | Modelo padrão do Lightning Platform para páginas do site                                            |
| FileNotFound                           | FileNotFound                           | 62            | Página padrão do Lightning Platform/Dados não encontrados                                           |
| BandwidthExceeded                      | BandwidthExceeded                      | 62            | Página padrão Limite excedido do Lightning Platform                                                 |
| Exception                              | Exception                              | 62            | Página padrão do Lightning Platform para erros pós-autenticação                                     |
| InMaintenance                          | InMaintenance                          | 62            | Página padrão Em manutenção do Lightning Platform                                                   |
| Unauthorized                           | Unauthorized                           | 62            | Página padrão Autorização obrigatória do Lightning Platform                                         |
| UnderConstruction                      | UnderConstruction                      | 62            | Página padrão Em construção do Lightning Platform                                                   |
| IdeasHome                              | IdeasHome                              | 62            | Página inicial padrão do Lightning Platform para sites de ideias                                    |
| AnswersHome                            | AnswersHome                            | 62            | Página inicial padrão do Lightning Platform para sites de Respostas                                 |
| CommunitiesTemplate                    | CommunitiesTemplate                    | 62            | Modelo padrão para as páginas de experiências                                                       |
| CommunitiesLogin                       | CommunitiesLogin                       | 62            | Página padrão de login das experiências                                                             |
| CommunitiesLanding                     | CommunitiesLanding                     | 62            | Página de destino padrão das experiências                                                           |
| CommunitiesSelfReg                     | CommunitiesSelfReg                     | 62            | Página padrão de registro automático das experiências                                               |
| CommunitiesSelfRegConfirm              | CommunitiesSelfRegConfirm              | 62            | Página padrão de confirmação de registro automático das experiências                                |
| MicrobatchSelfReg                      | MicrobatchSelfReg                      | 62            | Processe solicitações de autorregistro em lotes, em vez de individualmente                          |
| FSLGanttMapSF                          | FSLGanttMapSF                          | 64            | -                                                                                                   |
| FSLGanttMapSFDev                       | FSLGanttMapSFDev                       | 64            | -                                                                                                   |
| vf0018_ResourceLB_RelatedLists         | vf0018_ResourceLB_RelatedLists         | 64            | -                                                                                                   |
| vf004_ResourceChatter                  | vf004_ResourceChatter                  | 64            | -                                                                                                   |
| vf005_AbsenceChatter                   | vf005_AbsenceChatter                   | 64            | -                                                                                                   |
| vf017_IncompleteReason                 | vf017_IncompleteReason                 | 64            | -                                                                                                   |
| vf0993_ServiceChatter                  | vf0993_ServiceChatter                  | 64            | -                                                                                                   |
| vf0994_WorkWorderLineItemRelatedLists  | vf0994_WorkWorderLineItemRelatedLists  | 64            | -                                                                                                   |
| vf0996_WorkOrderChatter                | vf0996_WorkOrderChatter                | 64            | -                                                                                                   |
| vf0997_WorkOrderLineItemChatter        | vf0997_WorkOrderLineItemChatter        | 64            | -                                                                                                   |
| AppointmentBookingCommunitiesVf        | AppointmentBookingCommunitiesVf        | 64            | -                                                                                                   |
| AppointmentBookingVf                   | AppointmentBookingVf                   | 64            | -                                                                                                   |
| CrewManagement                         | CrewManagement                         | 64            | -                                                                                                   |
| CrewsResourceLightbox                  | CrewsResourceLightbox                  | 64            | -                                                                                                   |
| CrewsSaLightbox                        | CrewsSaLightbox                        | 64            | -                                                                                                   |
| CrewsWorkorderLightbox                 | CrewsWorkorderLightbox                 | 64            | -                                                                                                   |
| CrewsWorkorderLineItemLightbox         | CrewsWorkorderLineItemLightbox         | 64            | -                                                                                                   |
| EmergencyLightbox                      | EmergencyLightbox                      | 64            | -                                                                                                   |
| EmergencyWizard                        | EmergencyWizard                        | 64            | -                                                                                                   |
| FilterEditor                           | FilterEditor                           | 64            | -                                                                                                   |
| GanttPalette                           | GanttPalette                           | 64            | -                                                                                                   |
| GetCandidates                          | GetCandidates                          | 64            | -                                                                                                   |
| Integrity_Checker                      | Integrity_Checker                      | 64            | -                                                                                                   |
| OnboardingWizard                       | OnboardingWizard                       | 64            | -                                                                                                   |
| ResourceUnited                         | ResourceUnited                         | 64            | -                                                                                                   |
| Vf001GroupOnWorkRules                  | Vf001GroupOnWorkRules                  | 64            | -                                                                                                   |
| Vf002GroupOnObjectives                 | Vf002GroupOnObjectives                 | 64            | -                                                                                                   |
| vf0008_BundlerDetailsLightBox          | vf0008_BundlerDetailsLightBox          | 64            | -                                                                                                   |
| vf001_ServiceExpert                    | vf001_ServiceExpert                    | 64            | -                                                                                                   |
| vf001_optimizationViewer               | vf001_optimizationViewer               | 64            | -                                                                                                   |
| vf002_ServiceExpertLightboxForm        | vf002_ServiceExpertLightboxForm        | 64            | -                                                                                                   |
| vf002_ServiceExpertLightboxForm_Edit   | vf002_ServiceExpertLightboxForm_Edit   | 64            | -                                                                                                   |
| vf011_ResourceLightboxForm             | vf011_ResourceLightboxForm             | 64            | -                                                                                                   |
| vf012_AbsenceLightboxForm              | vf012_AbsenceLightboxForm              | 64            | -                                                                                                   |
| vf012_AbsenceLightboxForm_Edit         | vf012_AbsenceLightboxForm_Edit         | 64            | -                                                                                                   |
| vf015_ChangeServiceStatus              | vf015_ChangeServiceStatus              | 64            | -                                                                                                   |
| vf016_CompletionForm                   | vf016_CompletionForm                   | 64            | -                                                                                                   |
| vf017_AccountLightbox                  | vf017_AccountLightbox                  | 64            | -                                                                                                   |
| vf023_CalendarEditor                   | vf023_CalendarEditor                   | 64            | -                                                                                                   |
| vf034_Skill_Selector_V2_Resource_Page  | vf034_Skill_Selector_V2_Resource_Page  | 64            | -                                                                                                   |
| vf038_Skill_Selector_V2_WorkOrder_Page | vf038_Skill_Selector_V2_WorkOrder_Page | 64            | -                                                                                                   |
| vf039_Skill_Selector_V2_WorkType_Page  | vf039_Skill_Selector_V2_WorkType_Page  | 64            | -                                                                                                   |
| vf040_Skill_Selector_V2_WOLI_Page      | vf040_Skill_Selector_V2_WOLI_Page      | 64            | -                                                                                                   |
| vf066_settings                         | vf066_settings                         | 64            | -                                                                                                   |
| vf078_CapacityCalendar                 | vf078_CapacityCalendar                 | 64            | -                                                                                                   |
| vf079_ResourceCalendar                 | vf079_ResourceCalendar                 | 64            | -                                                                                                   |
| vf0995_WorkWorderRelatedLists          | vf0995_WorkWorderRelatedLists          | 64            | -                                                                                                   |
| vf0998_WorkOrderLineItemLightbox       | vf0998_WorkOrderLineItemLightbox       | 64            | -                                                                                                   |
| vf0998_WorkOrderLineItemLightbox_Edit  | vf0998_WorkOrderLineItemLightbox_Edit  | 64            | -                                                                                                   |
| vf0999_WorkOrderLightbox               | vf0999_WorkOrderLightbox               | 64            | -                                                                                                   |
| vf0999_WorkOrderLightbox_Edit          | vf0999_WorkOrderLightbox_Edit          | 64            | -                                                                                                   |
| vf103_SchedulePolicyChart              | vf103_SchedulePolicyChart              | 64            | -                                                                                                   |
| vf112_ResourcePriorityFieldChooser     | vf112_ResourcePriorityFieldChooser     | 64            | -                                                                                                   |
| vf739_ComplexWork                      | vf739_ComplexWork                      | 64            | -                                                                                                   |
| vf_EnhancedMatchRule                   | vf_EnhancedMatchRule                   | 64            | -                                                                                                   |
| DWPropostaPersonalizada                | DWPropostaPersonalizada                | 58            | -                                                                                                   |
| DWPropostaPersonalizadaOpp             | DWPropostaPersonalizadaOpp             | 61            | -                                                                                                   |
| PublicFilleView                        | PublicFilleView                        | 61            | -                                                                                                   |
| Assign Users                           | Assign_Users                           | 43            | -                                                                                                   |
| TrailheadSetup                         | TrailheadSetup                         | 38            | -                                                                                                   |
| TrailheadTest                          | TrailheadTest                          | 38            | Only for use by Salesforce.com support to help troubleshoot. Should not be used for other purposes. |
| Unassign_Users                         | Unassign_Users                         | 43            | -                                                                                                   |
