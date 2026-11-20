# Validador e Auditor de SEO para Imagens e Acessibilidade

[![Validador SEO Imagens](https://img.shields.io/badge/TAVARDT-Image%20SEO-5b3cf5.svg)](https://tools.tavardt.com/br/validador-seo-imagens/)
[![Jurisdicao](https://img.shields.io/badge/Jurisdicao-Brasil-00C853.svg)](https://ag.tavardt.com/br/)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)

Auditoria de atributos alt, adocao de formatos de nova geracao (WebP/AVIF), dimensoes de layout e nomes de arquivo semanticos.

Desenvolvido e mantido pela divisao de arquitetura semantica e acessibilidade web da **[TAVARDT Brasil](https://ag.tavardt.com/br/)**.

---

## Capacidades de Auditoria de SEO para Imagens

* **Inspecao de Atributos Alt e Acessibilidade**: Analise de cobertura de texto alternativo (`alt`), detectando imagens sem descricao ou com textos genericos/vazios.
* **Adocao de Formatos de Nova Geracao**: Auditoria de utilizacao de formatos modernos (WebP e AVIF) em substituicao a arquivos legados (JPEG, PNG e GIF).
* **Deteccao de Dimensoes e Mitigacao de CLS**: Verificacao da presenca de atributos `width` e `height` explicitos para eliminar oscilacoes de layout.
* **Auditoria de Carregamento Assincrono**: Identificacao de diretivas `loading="lazy"` para otimizacao do consumo de dados e aceleracao do FCP.
* **Indice de Otimizacao de Imagens**: Pontuacao tecnica quantitativa de 0 a 100 com alertas priorizados.

---

## Instalacao e Execucao

Requer Python 3.8 ou superior sem necessidade de pacotes externos adicionais.

```bash
git clone https://github.com/TAVARDT-Brasil/image-seo-validator-br.git
cd image-seo-validator-br
python image_seo_validator.py https://empresa.com.br
```

Para gerar a saida em formato estruturado JSON para integracao em pipelines:

```bash
python image_seo_validator.py https://empresa.com.br --json
```

---

## Diagnostico Completo na Web

Para auditoria aprofundada de imagens e analise visual de catalogo:

* **[Validador de SEO para Imagens Oficial](https://tools.tavardt.com/br/validador-seo-imagens/)**
* **[Portal Corporativo TAVARDT Brasil](https://ag.tavardt.com/br/)**

---

## Consultoria em Acessibilidade Visual e Performance

Para otimizacao de catalogos digitais e conformidade com Diretrizes de Acessibilidade W3C WCAG e SEO Google, contate os especialistas da **[TAVARDT Brasil](https://ag.tavardt.com/br/contato/)**.
