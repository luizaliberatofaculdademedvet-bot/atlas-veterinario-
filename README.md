# Vet Atlas 3D

Atlas veterinário educacional em ambiente web, construído para estudo anatômico em português e em latim, com visualização 3D integrada a uma interface de sistemas e estruturas.

## Visão geral

- pesquisa por estrutura anatômica em português ou latim
- seleção por sistema: esquelético, muscular, nervoso, digestório, respiratório, cardiovascular, urinário e genital
- visualização didática com rotação, zoom e seleção por clique
- filtros de camada: visão geral, esqueleto e órgãos
- suporte a modelo GLB local para uso didático e extensão do atlas
- referência estruturada a fontes acadêmicas e à nomenclatura veterinária internacional

## Referências anatômicas

Este projeto é um catálogo didático inicial e não substitui a nomenclatura oficial da disciplina. Para validação rigorosa de termos, estrutura, uso por espécie e formulários, consulte:

- WAVA / ICVGAN — Nomina Anatomica Veterinaria: https://www.wava-amav.org/nav/
- University of Minnesota — Veterinary Anatomy: https://vanat.cvm.umn.edu/

## Observações importantes

- A visualização 3D incluída no repositório é uma representação esquemática e didática.
- O atlas não substitui dissecação, atlas veterinário oficial, orientação docente, documentação de espécie e consulta especializada.
- Modelos GLB carregados localmente no navegador são tratados como dados locais; o arquivo não é enviado para o servidor.
- Para uso em ambiente acadêmico com alta exigência, os termos e estruturas devem ser revisados por anatomista veterinário.

## Como abrir

Basta publicar o repositório em GitHub Pages ou servir a pasta via servidor HTTP local. A página usa módulos do Three.js carregados por CDN, então a conexão à internet é necessária para o funcionamento do motor 3D.

## Observação final

Este atlas é um ponto de partida para um sistema universitário real. O passo seguinte ideal é a integração de um catálogo maior, espécie por espécie, com dados em JSON/BD validados por atlas de referência e por profissionais da área.
