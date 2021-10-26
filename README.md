- 👋 Hi, I’m @muniz123456
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
muniz123456/muniz123456 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
<! DOCTYPE html >
< html >

< cabeça >
  <! - Conjunto de caracteres (definido pela ASCII) ->   
  < meta  charset = " UTF-8 " >
  < title > Cardápio </ title >
  <! - direcioanamento de link ao arquivo de script externo ->
  <! - Bootstrap - CSS ->
  < link  href = " node_modules / bootstrap / dist / css / bootstrap.min.css " rel = " stylesheet " >

</ head >

< corpo >
  < cabeçalho >
    <! - Barra de ferramentas = agrupamento de uam serie de botões ->
    < nav  class = " navbar navbar-expand-lg navbar-dark bg-primary " >
      < div  class = " container-fluid " >
        < A  class = " navbar-brand " href =" # " >
          Café
          < pequena > Arábica </ pequena >
        </ a >

        < button  class = " navbar-toggler " type = " button " data-bs-toggle = " collapse " data-bs-target = " #navbarNav " aria-controls = " navbarNav " aria- extended = " false " aria-label = " Alternar navegação " >
          < span  class = " navbar-toggler-icon " > </ span >
        </ botão >
        <! - Cabeçalho de navegação ->
        < div  class = " collapse navbar-collapse " id = " navbarNav " >
          < ul  class = " navbar-nav " >
            < li  class = " nav-item " >
              < A  class = " nav-link " href =" ./index.html " > Início </ a >
            </ li >
            < li  class = " nav-item " >
              < A  class = " nav-link ativo " aria-current =" página " href =" # " > Cardápio </ a >
            </ li >
            < li  class = " nav-item " >
              < A  class = " nav-link " href =" # " > Sobre </ a >
            </ li >
          </ ul >
        </ div >
      </ div >
    </ nav >

  </ header >
  < principal >
    <! - my-3 = espaçamento entre as margens dos elementos ->
    < section  class = " my-3 " >

      <! - Grade ->
      < div  class = " container " >
        <! - Botão para inserir elementos ->
        < button  type = " button " class = " btn btn-secondary rounded-circle " data-bs-toggle = " modal " data-bs-target = " #exampleModal " >
          +
        </ botão >
        <! - Modal (reponsavel por adicionar o novo elemento) ->
        < div  class = " modal fade " id = " exampleModal " tabindex = " -1 " aria-labelledby = " exampleModalLabel " aria-hidden = " true " >
          < div  class = " modal-dialog " >
            < div  class = " modal-content " >
              < div  class = " modal-header " >
                < h5  class = " modal-title " id = " exampleModalLabel " > Adicionar novo item </ h5 >
                < button  type = " button " class = " btn-close " data-bs-despedir = " modal " aria-label = " Fechar " > </ button >
              </ div >
              <! - Descrição e caixas (entrada) para adicionar novo elemento ->
              < div  class = " modal-body " >
                < h5 > Nome </ h5 >
                < input  type = " text " class = " form-control " >
              </ div >

              < div  class = " modal-body " >
                < h5 > Descrição </ h5 >
                < input  type = " text " class = " form-control " >
              </ div >
              < div  class = " modal-body " >
                < h5 > Preço </ h5 >
                < input  type = " text " class = " form-control " >
              </ div >
              < div  class = " modal-body " >
                < h5 > Endereço da Imagem </ h5 >
                < input  type = " text " class = " form-control " >
              </ div >
              < div  class = " modal-footer " >
                <! - botões de gerenciamento ->
                < button  type = " button " class = " btn btn-success " class = " btn btn-primary " > Adicionar </ button >
                < button  type = " button " class = " btn btn-warning " >
                  Limpar
                </ botão >
                < botão  type = " botão " class = " btn btn-perigo " data-bs-despedir = " modal " > Fechar </ botão >

              </ div >
            </ div >
          </ div >
        </ div >

        <! - Linha ->
        < div  id = " itens-cardapio " class = " row " >

          <! - Colunas ->

          <! - antes do fim ->
        </ div >

    </ seção >

  </ main >
  < rodapé > </ rodapé >

  <! - Cardápio = pegando o conteudo do JS ->
  < script  src = " ./js/cardapio.js " > </ script >
  <! - direcioanamento de link ao arquivo de script externo ->
  <! - Bootstrap - Js ->
  < script  src = " node_modules / bootstrap / dist / js / bootstrap.bundle.min.js " > </ script >
</ body >

</ html >
