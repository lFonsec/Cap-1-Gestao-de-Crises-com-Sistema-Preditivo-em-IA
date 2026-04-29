# Cap-1-Gestao-de-Crises-com-Sistema-Preditivo-em-IA

# Instalação

Clone o repositório:

git clone https://github.com/seu-usuario/projeto-pico-risco.git
cd projeto-pico-risco

# Execução do Sistema
Abra o arquivo Cap_1_Gestao_de_Crises_com_Sistema_Preditivo_em_IA.ipynb no google collab

# Fluxo do Sistema
* Primeiro tem a entrada dos dados do paciente
* Depois o agente orquestrador aciona o analista de risco
* Então o modelo retorna a probabilidade de pico de risco
* Por fim o resultado é enviado ao Agente de Protocolos
* O sistema retorna:
* Probabilidade de risco
* Classificação (Baixo / Médio / Alto) com o protocolo sugerido

# Exemplo de Entrada
```
{
  "idade": 65,
  "frequencia_cardiaca": 120,
  "spo2": 90,
  "carga_sistema": 0.85,
  "disponibilidade_recursos": 0.3
}
```
# Exemplo de Saída
```
{
  "probabilidade": 0.82,
  "classificacao": "Alto",
  "protocolo": "UTI, monitoramento contínuo, suporte ventilatório"
}
```
