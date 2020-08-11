<template>
  <div>
    <div class="bg-blue-500 ">
      <div class="container">
        <header class="flex justify-center py-8 sm:justify-start">
          <img src="~assets/images/logo.png" alt="">
        </header>
        <div class="pt-12 pb-8">
          <h2 class="text-3xl uppercase text-green-500 font-medium">EBOOK:</h2>

          <div class="md:flex">
            <div class="md:w-1/2">
              <h1 class="font-sans text-white text-9xl font-semibold leading-tight">
                Fortaleça seu negócio em época de coronavírus com o nosso e-book
              </h1>
            </div>
          </div>
        </div>
      </div>
    </div>

    <div class="container pt-8 text-gray-500 text-lg md:flex mb-12">
      <div class="md:w-1/2 pr-8">
        <p class="md:mb-6">
          Com o novo cenário em que temos vivido, empresas que utilizam a tecnologia para atender seus consumidores tornam-se mais fortes e estratégicas. Com o planejamento, controle e o suporte das Supply Chain Finances, há mais organização, eficiência, segurança e transparência nas atividades e no relacionamento entre Fornecedores, Compradores e Financiadores.
        </p>

        <p class="md:mb-6">
          A Cashforce traz o e-book:<span class="text-blue-500 font-semibold"> Tecnologia como solução para empresas no cenário atual</span>, um material exclusivo para você saber como a tecnologia e os processos de gestão alinhados são essenciais para a cadeia de suprimentos superar a crise causada pelo novo coronavírus.
        </p>

        <p class="md:mb-6">
          <span class="text-blue-500 font-semibold">Baixe o e-book</span> agora mesmo e prepare sua empresa para este novo cenário.
        </p>

        <div class="hidden md:flex mt-32 mb-8 justify-between items-center">
          <div class="w-1/2">
            <span class="text-blue-600">© CashForce 2020</span>
          </div>

          <div class="flex justify-between w-1/2">
            <img class="pl-2" src="~assets/images/linkedin.png" alt="LinkeDin">
            <button class="button px-6">Quero conhecer</button>
          </div>
        </div>
      </div>

      <div class="mt-8 md:w-1/2 md:pl-8 md:mt-0">
        <h2 class="font-sans text-blue-600 text-5xl mb-4"> Baixe esse conteúdo gratuitamente</h2>

        <form action="">

          <label class="form-label" for="name">Seu nome</label>
          <input class="form-input" type="text" id="name" name="fname" value="" placeholder="Seu nome">

          <label class="form-label" for="email">E-mail de trabalho</label>
          <input class="form-input" type="text" id="email" name="fname" value="" placeholder="Seuemail@dominio.com">

          <label class="form-label" for="phone">Número de telefone</label>
          <input class="form-input" type="text" id="phone" name="fname" value="" placeholder="(11) 99999-9999">

          <label class="form-label" for="company">Nome da empresa</label>
          <input class="form-input" type="text" id="company" name="fname" value="" placeholder="nome da empresa">

          <label class="form-label" for="role">Cargo</label>
          <input class="form-input" type="text" id="role" name="fname" value="" placeholder="Seu cargo">

          <label class="form-label" for="employees">Funcionários</label>
          <select class="form-input bg-white" name="employees" id="employees">
             <option value="" disabled selected>Selecione</option>
          </select>

          <label class="form-label" for="segment">Em qual segmento sua empresa se encaixa?</label>
          <select class="form-input bg-white" name="segment" id="segment">
             <option value="" disabled selected>Selecione</option>
          </select>



          <div class="flex justify-end mt-6">
            <input class="button px-20 " type="submit" value="enviar">
          </div>
        </form>
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style lang="postcss">
.form-label {
  @apply block text-sm text-blue-600 font-bold mb-1;
}

.form-input {
  @apply block border-solid border border-blue-600 w-full px-4 py-2 rounded-md mb-4;
}

.button {
  @apply bg-green-500 py-2 text-sm text-blue-600 font-bold rounded-md;
}

</style>
