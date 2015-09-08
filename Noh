package tarefa_4;

public class Noh {

	public Object Valor = null;
	public Noh proximo = null;

	public Noh(Object valor) {
		super();
		this.Valor = valor;
	}

	public static void main(String[] args) {
		Noh cabeca = new Noh("a");
		cabeca.add("b");
		cabeca.add("c");
		System.out.println(cabeca);
	}

	private void add(Object conteudo) {
		if (this.proximo == null) {
			proximo = new Noh(conteudo);
		} else {
			proximo.add(conteudo);

		}
	}
	
	@Override
	public String toString() {
		String str="";
		str+=this.Valor;
		if (proximo!=null)
		{
			str+=proximo.toString();
		}
		return str;
	}

}
