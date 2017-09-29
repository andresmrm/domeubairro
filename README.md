**VERSÃO ANTIGA, DESCONTINUADA.**

- [Grupo com todos os repositórios da nova versão](https://gitlab.com/cuidandodomeubairro)
- [Cópia desse repositório dentro do novo grupo, para fins históricos](https://gitlab.com/cuidandodomeubairro/cuidando-antigo-v1)

---

## Cuidando do meu Bairro 

http://cuidando.org.br

#### Dependências

Dependências de módulos Perl (instaláveis através do CPAN):
- JSON
- JSON::XS (Opcional, geralmente instalado junto com o módulo JSON)
- WWW::Mechanize
- DBI
- DBD::SQLite

Podem ser instaladas com:

	# apt-get install libdbd-perl libdbd-sqlite3-perl libjson-perl libwww-mechanize-perl

Dependências de módulos Python 3:
- xlrd

Podem ser instaladas com:

	# easy_install xlrd

#### Atualização dos Dados

	cd processador/src
	python auto.py <ANO>
