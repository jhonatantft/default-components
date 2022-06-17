lerna exec
  - vai pegar qualquer comando e executá-lo e todos os pacotes diferentes
  - instrui o babel a executar em paralelo cada pacote, puxando da pasta src e compilando na pasta /lib
--root-mode upward
 - diz ao babel que node_modules estão localizados na raiz ao invés de aninhados dentro de cada um dos pacotes individuais. isso evita que cada pacote tenha o mesmo node_modules e extrai até a taiz