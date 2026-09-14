# proj
# B. Modos de condução e distância segura
#O modo de condução altera o tempo de reação considerado pelo módulo
#autônomo:
#• 1 (esportivo) = 1.0 segundo
#• 2 (normal) = 1.5 segundos
#• 3 (seguro) = 2.0 segundos
#A distância segura exigida unir a regra do tempo de reação com o cálculo
#físico de frenagem.
#Fórmula: 𝐷𝑖𝑠𝑡𝑎𝑛𝑐𝑖𝑎_𝑆𝑒𝑔𝑢𝑟𝑎 = (𝑣𝑚𝑠 × 𝑇𝑒𝑚𝑝𝑜_𝑅𝑒𝑎𝑐𝑎𝑜) +
#𝑣𝑚𝑠
#2
#2×𝑎𝑡𝑟𝑖𝑡𝑜×9.81
#(nota: todas as velocidades fornecidas em km/h precisarão ser convertidas para m/s dividindo por 3.6 antes de aplicar a fórmula)
# a = vel_rel
# b = tempo_reacao
#unidade de medida como variavel
import math
def converter_km_para_metros(valor_km):
   
    valor_convertido = valor_km / 3,6
    
    # Retorna apenas o resultado numérico com no máximo 1 casa decimal
    return round(valor_convertido, 1)

# Solicita o valor diretamente para o usuário
usuario_input = float(input("Digite o valor em km: "))

# Executa a função e exibe o resultado limpo
resultado = converter_km_para_metros(usuario_input)
print(resultado)
 
def multiplicar():
  print("""Tempo de reação: 
    Opção1(esportivo) = 1.0 seg
    Opção2(normal) = 1.5 seg
    Opção3(seguro) = 2.0 seg""")
  
  tr = float(input("Opção: "))

  print("""Nível do atrito na via:
    Opção1: pista seca
    Opção2: pista molhada
    Opção3: baixa aderência""")
        
  at = int(input("Opção: "))
multiplicar()
   
 #vm = float(vkm / 3.6)
 #ds1 = vm * tr
 #ds2 = vm**2
 #ds3 = 
 #print(f'O resultado: {resultado}')
#multiplicar()

#dist_seg
#def convert (a,b)
#a = 
