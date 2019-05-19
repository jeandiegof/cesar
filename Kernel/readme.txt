


====================================================================================================================
    Trabalho do Cesar - 2019/1
====================================================================================================================

    Aqui você encontra os arquivos necessários para implementar o kernel.

    Os arquivos são os seguintes:

        app_profB.mem      		-> Arquivo com uma aplicação que utiliza todas as funções de seu kernel
					   Esse arquivo deverá ser carregado no simulador, APÓS carregado seu kernel (usando carga parcial)
        TrabalhoCesar2019_1_Parte2.pdf	-> Especificação do trabalho
        FuncoesDoKernel.pdf		-> Descrição das funções que você deve implementar no kernel
        REFERENCIA_KERNEL.CED		-> Arquivo a partir do qual você deve desenvolver a sua solução de kernel
	readme.txt			-> Este arquivo
	



====================================================================================================================
	CARGA PARCIAL
====================================================================================================================

    Procedimento para "juntar" (mesclar) o seu kernel com a aplicação fornecida pelo professor.
	
    Esse procedimento é necessário para colocar a aplicação do professor junto com seu kernel em execução.
	
    Procedimento
        1) Carregue, normalmente, no simulador, o SEU arquivo de kernel (.MEM).
        2) Carregue, usando "carga parcial", no simulador, o programa app_prof.mem, fornecido pelo professor.
           Carregar a área de 256 a 32767 para o endereço 256 da memória do simulador.
        3) Zere o Program Counter (R7) e inicie a execução



====================================================================================================================
    Quais os dados necessários para realizar a carga parcial no simulador?
====================================================================================================================

    Para realizar a carga parcial você deve usar no simulador o menu "Arquivo" >> "Carga Parcial"
	
    O simulador solicitará, então, as seguintes informações, em ordem:
        Arquivo: selecione o programa de aplicação desejado
        Endereço inicial da memória a copiar: 256
        Endereço final da memória a copiar: 32767
        Endereço de destino: 256



====================================================================================================================
    Como rodar, passo a passo, sua implementação
====================================================================================================================

	Como o seu kernel inicia a rodar no endereço H0000, você pode usar o "passo-a-passo" desde o início da execução.
	
	Caso você deseje rodar "passo-a-passo" dentro da interrupção, basta escrever o endereço desejado
	no campo "BP" do simulador (no canto inferior esquerdo) e comandar para executar o programa.

    Assim que o programa atingir o endereço programado, dentro da interrupção, a execução vai parar.
    A partir desse instante, você poderá executar seu programa passo a passo
	
	
