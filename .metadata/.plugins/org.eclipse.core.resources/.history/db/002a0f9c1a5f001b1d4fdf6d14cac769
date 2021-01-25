package br.senai.sp.jandira;

import br.senai.sp.jandira.model.Cliente;
import br.senai.sp.jandira.model.Conta;

public class App2 {

	public static void main(String[] args) {
	
//		Criação do Cliente
		Cliente pedro = new Cliente();
		pedro.setNome("Pedro Álvares Cabral");
		pedro.setCpf("562323565");
		pedro.setTelefone("(11)4512-8956");
		pedro.setCep("06687555");

//		Criar conta do Pedro
		Conta  contaPedro = new Conta();
		contaPedro.setTitular(pedro);
		contaPedro.depositar(100);
		contaPedro.setNumero("2222-2");
		
		System.out.println(contaPedro.getTitular().getTelefone());
	}

}
