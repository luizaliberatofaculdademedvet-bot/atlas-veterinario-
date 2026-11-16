# Vet Atlas 3D

Atlas web educacional de anatomia veterinária, em português, com visualização 3D baseada em Three.js.

## Abrir e executar

O visualizador 3D usa módulos carregados de CDN e, por isso, precisa de conexão à internet. Abra o site publicado no GitHub Pages (ou sirva a raiz do repositório por HTTP). A página também permite carregar localmente um modelo `.glb` pelo botão **Carregar modelo GLB**; o arquivo não é enviado para o servidor.

## Escopo anatômico e nomenclatura

O catálogo incluído é uma seleção inicial de estruturas com campos em português, latim e região. Ele não é uma cópia integral da *Nomina Anatomica Veterinaria* (NAV), nem substitui atlas, dissecação ou validação de docente. Confira formas, sinônimos, acentuação e aplicabilidade por espécie na edição vigente indicada pela disciplina/WAVA-ICVGAN. Termos latinos e traduções portuguesas são apresentados separadamente para evitar sugerir que sejam equivalências oficiais quando não validadas.

Referências para conferência:

- WAVA / ICVGAN, *Nomina Anatomica Veterinaria*: <https://www.wava-amav.org/nav/>
- University of Minnesota, Veterinary Anatomy: <https://vanat.cvm.umn.edu/>

Antes de uso curricular, peça revisão a um anatomista veterinário. Atualize o catálogo versionando cada termo com a edição, seção/página e espécie a que se aplica.

## Modelo 3D

O modelo gerado no navegador é uma ilustração esquemática de baixa fidelidade feita com primitivas Three.js. Ele serve para experimentar controles e camadas, não para ensinar topografia ou proporções anatômicas exatas. Não há arquivo anatômico GLB de alta fidelidade incluído. Para isso, use modelos próprios, licenciados para redistribuição e revisados por especialista; não redistribua modelos de atlas comerciais ou universitários sem autorização.

O carregamento de `.glb` é local no navegador. Os nomes de nós do GLB podem não corresponder aos termos do catálogo automaticamente; a seleção anatômica por nomenclatura requer que o modelo seja preparado e rotulado com metadados compatíveis.

## Tecnologias

- Three.js e OrbitControls para rotação, zoom, renderização e seleção por clique.
- GitHub Pages / hospedagem estática.
- O app depende de WebGL e de acesso à CDN do Three.js.
