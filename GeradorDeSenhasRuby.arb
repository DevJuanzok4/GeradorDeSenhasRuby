def gerar_senha(tamanho)
    caracteres = ('a'..'z').to_a + ('A'..'Z').to_a + (0..9).to_a
    senha = Array.new(tamanho) { caracteres.sample }.join
end

puts "Simulador de Gerador de Senhas"
print "Digite o tamanho da senha desejado: "
tamanho_senha = gets.chomp.to_i 

senha_gerada = gerar_senha(tamanho_senha)
puts "Senha Gerada: #{senha_gerada}"
