# FUNDATEC Folha De Pagamentos
Extração de dados com Requests para listar pagamentos da FUNDATEC - Fundação Paulistana de Educação, Tecnologia e Cultura da cidade de São Paulo

## Modo de usar

Execute o arquivo run.py:

```bash
python run.py
```

## Resultado

**Schema**

- empresa: string
- mes: string
- ano: string
- nome: string
- cargo: string
- lotacao: string
- admissao: string
- nascimento: string
- vencimentos: string
- encargos: string
- beneficios: string
- outras_remuneracoes: string
- vinculo: string
- detalhe_vinculo: string
- liminar: string
- arquivo_id: string

**Dados**

```json
{
    "empresa": "FUNDATEC",
    "mes": "Janeiro",
    "ano": "2018",
    "nome": "Marcio Pinto Ferreira",
    "cargo": "Contratado por Tempo Determinado",
    "lotacao": "ETSP Prof Makiguti",
    "admissao": "26/01/2006",
    "nascimento": "1968",
    "vencimentos": "R$14.918,51",
    "encargos": "R$3.923,68",
    "beneficios": "R$-",
    "outras_remuneracoes": "R$-",
    "vinculo": "CLT: contrato por tempo indeterminado",
    "detalhe_vinculo": "No concursado NO ocupante de cargo em comisso",
    "liminar": "-",
    "arquivo_id": "735c7632-c12e-465a-bb0e-98ada88ebab9"
}
```