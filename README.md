# Poo
classDiagram
    iPhone <|-- ReprodutorMusical
    iPhone <|-- AparelhoTelefonico
    iPhone <|-- NavegadorInternet

    class ReprodutorMusical{
      +String selecionarMusica
      +tocar()
      +pausar()
    }
    class AparelhoTelefonico{
      +String numero
      +ligar()
      +atender()
      +iniciarCorreioVoz()
    }
    class NavegadorInternet{
      +String exibirPagina 
      +adicionarNovaAba()
      +atualizarPagina()
    }
