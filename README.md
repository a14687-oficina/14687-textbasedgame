<h1> TextBasedGame <h1>
introducao = str(input("Deseja jogar este este jogo? (sim/não): "))
if introducao.lower() == "não":
  quit()
elif introducao.lower() == "sim":
  print ("=======================BEM VINDO A FLORESTA ENCANTADA=======================")
nome = str(input("\nPrimeiro de tudo diga me o seu nome: "))
print (f"\nBoa sorte, {nome}.")
print ("\nÀ tua frente, no coração de uma floresta densa e serena, três caminhos se abrem")

print ("\nO caminho da direita exala um aroma floral, e logo à frente, uma ponte de madeira atravessa um riacho brilhante sob a luz do sol.")
print ("\nO caminho do meio é banhado por uma luz suave ao longe, com o canto dos pássaros criando uma atmosfera de paz ao redor.")
print ("\nO caminho da esquerda é adornado por flores vibrantes e um aroma doce, com a luz do sol filtrando-se entre as folhas e iluminando o ambiente com alegria.")

def direita():
    print("\nVocê escolheu o caminho da direita.")

def meio():
    print("\nVocê escolheu o caminho do meio.")

def esquerda():
    print("\nVocê escolheu o caminho da esquerda.")

  # Inicializa as variáveis
direita1 = None
esquerda1 = None
meio1 = None

  # Solicita a escolha do usuário
escolha8 = input("\nPara onde quer ir (direita, meio ou esquerda): ").strip().lower()

  # Verifica a escolha e executa a ação correspondente
if escolha8 == "direita":
    direita() 
    print("\nVocê avança pelo caminho da direita, sentindo um aroma floral delicioso. À medida que caminha, uma ponte de madeira aparece à sua frente, cruzando um riacho que brilha sob a luz do sol.")
    direita1 = input("A1) Seguir um suave aroma de flores. Você sente que ele pode levá-lo a um lugar encantador \nA2)Observar uma ponte de madeira que cruza um riacho. O que estará do outro lado?\n-  ")

elif escolha8 == "meio":
    meio()
    print("\nVocê avança pelo caminho do meio, onde uma luz suave brilha à distância. O som melodioso dos pássaros encanta seus ouvidos, e você se sente em paz neste ambiente tranquilo.")
    meio1 = input("B1) Avançar em direção a uma luz brilhante que pisca à distância. O que poderia ser?\nB2) Parar para ouvir os pássaros cantando. As melodias parecem contar uma história.\n- ")

elif escolha8 == "esquerda":
    esquerda()
    print("Você avança pelo caminho da esquerda, que é repleto de flores coloridas e exala um aroma doce. A luz do sol brilha suavemente entre as folhas, criando um ambiente alegre.")
    esquerda1 = input("C1) Seguir o som de risadas infantis. Você se pergunta se há crianças brincando.\nC2) Parar para admirar as flores coloridas ao longo do caminho. Elas estão em plena floração e exalam aromas deliciosos.\n- ")

else:
    print("Escolha inválida! Por favor, escolha entre 'direita', 'meio' ou 'esquerda'.")

direita2 = None
esquerda2 = None
meio2 = None
direita3 = None
esquerda3 = None
meio3 = None
if direita1 == "A1":
  print ("\n O aroma fica mais intenso, levando-o a uma clareira repleta de flores exóticas. Uma estranha neblina surge ao redor das flores, tornando o ar denso e misterioso.")
  direita2 = str(input("\nA1) Caminhar pela neblina, esperando encontrar algo além dela.\nA2) Prender a respiração e avançar rapidamente, torcendo para que seja seguro.\n- " ))
elif direita1 == "A2":
  print ("\n Você atravessa a ponte. Ao chegar do outro lado, percebe uma abertura na terra,como se alguém houvesse enterrado algo valioso.")
  direita3 = str(input("\nA1) Escavar e ver o que encontra (pode ser o tesouro ou algo perigoso).\nA2)Continuar andando, evitando escavar para não correr riscos.\n- "))


if meio1 == "B1":
  print ("\n Você avança em direção à luz brilhante que pisca à distância. Ao atravessar o portal, um campo mágico se revela, repleto de cores vibrantes e criaturas fantásticas.")
  meio2 = str(input("B1)Explorar o campo.\nB2)Observar as criaturas ao redor.\n- "))
elif meio1 == "B2":
  print ("\n Você para para ouvir os pássaros cantando. As melodias suaves parecem contar uma história antiga, cheia de alegria e mistério. Enquanto escuta, percebe que os pássaros voam em círculos, como se estivessem formando um padrão no céu.")
  meio3 = str(input("\nB1)Tentar seguir o padrão dos pássaros.\nB2)Fechar os olhos e deixar a música te envolver.\n- "))



if esquerda1 == "C1":
  print ("\nVocê segue o som de risadas infantis, que ecoam entre as flores. À medida que avança, a alegria das vozes se torna mais clara, e você se pergunta se há crianças brincando por perto.\nLogo, você chega a uma clareira, onde várias crianças estão dançando e brincando. Elas parecem felizes e cheias de energia.")
  esquerda2 = str(input("\nC1)Juntar-se à dança e brincar com as crianças.\nC2)Observar de longe e sorrir com a cena.\n- "))
elif esquerda1 == "C2":
  print ("\nVocê para para admirar as flores coloridas ao longo do caminho. Elas estão em plena floração, exibindo uma paleta vibrante e exalando aromas deliciosos que enchem o ar.\nEnquanto observa, uma abelha passeia de flor em flor, e você se sente em paz, imerso na beleza do momento.")
  esquerda3 = str(input("\nC1)Tentar identificar as diferentes flores.\nC2)Sentar-se no chão e relaxar, apreciando a paisagem.\n- "))

direita4 = None
meio4 = None
esquerda4 = None
direita5 = None
meio5 = None
esquerda5 = None

if direita2 == "A1":
  print ("\nVocê decide caminhar pela neblina, curiosidade pulsando em seu coração. À medida que avança, a densa bruma envolve você, tornando tudo ao seu redor etéreo. De repente, você ouve um sussurro suave, como se a neblina estivesse tentando se comunicar.\nLogo, você chega a uma pequena fonte cristalina que brilha sob a luz filtrada pela neblina.")
  direita4 = str(input("\nA1)Beber da água da fonte.\nA2)Examinar a fonte mais de perto.\n- "))
elif direita1 == "A2":
 print ("\nVocê decide prender a respiração e avançar rapidamente pela neblina, torcendo para que seja seguro. Enquanto atravessa a bruma, a sensação de mistério aumenta, e você sente uma leve eletricidade no ar.\nAssim que sai da neblina, encontra-se em um jardim oculto, onde flores brilham em cores que você nunca viu antes. No centro do jardim, uma grande pedra polida reflete a luz de maneira mágica.")
direita5 = str(input("\nA1)Aproximar-se da pedra e tocá-la.\nA2)Explorar o jardim em busca de mais maravilhas.\n- "))

if meio2 == "B1":
  print ("")
  meio4 =
elif meio2 == "B2":
