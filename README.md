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
  < meta  charset = " UTF-8 " >
  < title > Cardápio </ title >

  <! - Bootstrap - CSS ->
  < link  href = " node_modules / bootstrap / dist / css / bootstrap.min.css " rel = " stylesheet " >

</ head >

< corpo >
  < cabeçalho >
    <! - Barra de ferramentas ->
    < nav  class = " navbar navbar-expand-lg navbar-dark bg-primary " >
      < div  class = " container-fluid " >
        < A  class = " navbar-brand " href =" # " >
          Café
          < pequena > Arábica </ pequena >
        </ a >

        < button  class = " navbar-toggler " type = " button " data-bs-toggle = " collapse " data-bs-target = " #navbarNav " aria-controls = " navbarNav " aria- extended = " false " aria-label = " Alternar navegação " >
          < span  class = " navbar-toggler-icon " > </ span >
        </ botão >

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
    < section  class = " my-3 " >

      <! - Grade ->
      < div  class = " container " >

        <! - Modal de acionamento do botão ->
< button  type = " button " class = " btn btn-primary " data-bs-toggle = " modal " data-bs-target = " #exampleModal " >
    Adicionar
  </ botão >
  
  <! - Modal ->
  < div  class = " modal fade " id = " exampleModal " tabindex = " -1 " aria-labelledby = " exampleModalLabel " aria-hidden = " true " >
    < div  class = " modal-dialog " >
      < div  class = " modal-content " >
        < div  class = " modal-header " >
          < h5  class = " modal-title " id = " exampleModalLabel " > Adicionar item </ h5 >
          < button  type = " button " class = " btn-close " data-bs-despedir = " modal " aria-label = " Fechar " > </ button >
        </ div >
        < div  class = " modal-body " >
          < formulário >
            < div  class = " mb-3 " >
              < label  for = " nome " class = " form-label " > Nome </ label >
              < input  type = " text " class = " form-control " id = " nome " >
            </ div >
            < div  class = " mb-3 " >
              < label  for = " preço " class = " form-label " > preço </ label >
              < input  type = " number " class = " form-control " id = " preço " >
            </ div >
            < div  class = " mb-3 " >
              < label  for = " desc " class = " form-label " > descrição do produto </ label >
              < input  type = " text " class = " form-control " id = " desc " >
            </ div >
            < div  class = " mb-3 " >
              < label  for = " end " class = " form-label " > endereço da imagem (local ou global) </ label >
              < input  type = " text " class = " form-control " id = " end " >
            </ div >
          </ form >
        </ div >
        < div  class = " modal-footer " >
          < button  type = " button " class = " btn btn-primary " > Fechar </ button >
          < button  type = " button " class = " btn btn-primary " > Limpar </ button >
          < button  type = " button " class = " btn btn-primary " > Adicionar </ button >  
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

  <! - Cardápio ->
  < script  src = " ./js/cardapio.js " > </ script >

  <! - Bootstrap - Js ->
  < script  src = " node_modules / bootstrap / dist / js / bootstrap.bundle.min.js " > </ script >
</ body >

</ html >
