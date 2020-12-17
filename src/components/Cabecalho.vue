<template>
  <header>
			<!-- Inicio cabeçalho -->
			<nav class="navbar navbar-expand-sm navbar-light bg-primary">
				<div class="container">
					<!-- logo, classe serve para remover o link e definir como logo -->
					<a href="#" class="navbar-brand">
						<img
							src="../assets/web-design-library.png"
							width="50"
							height="50"
						/>
						Crud
					</a>

					<button
						class="navbar-toggler"
						data-toggle="collapse"
						data-target="#nav-principal"
					>
						<span class="navbar-toggler-icon"></span>
					</button>

					<div class="collapse navbar-collapse" id="nav-principal">
						<!-- navegaçao -->
						<!-- Ao usar margem esquerda(ML), ele joga automatico para direita -->
						<ul class="navbar-nav ml-auto">
							<li class="nav-item">
								<a href="#" class="nav-link">Pessoa</a>
							</li>
							<li class="nav-item">
								<a href="#" class="nav-link">Estado</a>
							</li>
							<li class="nav-item">
								<a href="#" class="nav-link">Endereço</a>
							</li>
							<li class="nav-item">
								<a href="#" class="nav-link">Contato</a>
							</li>
							<li class="nav-item">
								<a href="./Cidade.vue" class="nav-link">Cidade</a>
							</li>
						</ul>
					</div>
				</div>
			</nav>
		</header>
</template>

<script>

export default {
  name: 'Cabecalho',
  props: {
  }
}
</script>
