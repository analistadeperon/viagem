# viagem

<hello name="{{ name }}"></hello>
<p>
  Start editing to see some magic happen :)
</p>
<!DOCTYPE html>
<html lang="pt-br">
<head>
<meta charset="utf-8">
 <title> Calculadora Flex </title>
</head>
<body>
 <header>
 <h1> Calculadora Flex </h1>
 </header>
 <div class="content" >
 <form class="form">
<div>
 <label for="Gas_Cons">Consumo com Gasolina:</label>
 <input type="number" name="Gas_Cons" id="Gas_Cons">
</div>
<div>
 <label for="Eta_Cons">Consumo com Etanol:</label>
 <input type="number" name="Eta_Cons" id="Eta_Cons">
</div>
<div>
 <label for="Gas_Price">Gasolina:</label>
 <input type="number" name="Gas_Price" id="Gas_Price"
 placeholder="Preço da Gasolina">
</div>
<div>
 <label>Etanol:</label>
 <input type="number" name="Eta_Price" id="Eta_Price"
 placeholder="Preço do Etanol">
</div>
 </form>
 </div>
 <div>
 <button type="button">Gasolina ou Etanol?</button>
 </div>
</body>
</html>
<form>
<fieldset>
<legend>Informação</legend>
<p><label>E-mail <input type="email" name="email" placeholder="user@domain.com"></label></p>
<p><label>Web site <input type="url" name="website" placeholder="http://www.domain.com/"></label></p>
<p><label>Telefone <input type="tel" name="fone" placeholder="123-123-1234"></label></p>
</fieldset>
<p><button type="submit">Submeter</button></p>
</form>
<form>
<p><label>cor de Fundo <input type="color" name="bg"></label></p>
<p><label>cor da Frente <input type="color" name="fg"></label></p>
<p><button type="submit">Submeter</button></p>
</form>
<div class="container">
      <div class="py-5 text-center">
        <img class="d-block mx-auto mb-4" src="https://feiraopassagensaereas.com.br/wp-content/uploads/2020/07/agencia-de-viagens-corporativas-tristar.jpg" alt="" width="740" height="740">
        <h2>Formulário de checkout</h2>
        <p class="lead">Abaixo temos um exemplo de formulário construído com controles de formulário Bootstrap. Cada campo obrigatório possui um estado de validação que é ativado quando tenta-se enviar o formulário sem completá-lo.</p>
      </div>

      <div class="row">
        <div class="col-md-4 order-md-2 mb-4">
          <h4 class="d-flex justify-content-between align-items-center mb-3">
            <span class="text-muted">Seu carrinho</span>
            <span class="badge badge-secondary badge-pill">3</span>
          </h4>
          <ul class="list-group mb-3">
            <li class="list-group-item d-flex justify-content-between lh-condensed">
              <div>
                <h6 class="my-0">Nome do produto</h6>
                <small class="text-muted">Breve descrição</small>
              </div>
              <span class="text-muted">R$1200</span>
            </li>
            <li class="list-group-item d-flex justify-content-between lh-condensed">
              <div>
                <h6 class="my-0">Segundo produto</h6>
                <small class="text-muted">Breve descrição</small>
              </div>
              <span class="text-muted">R$800</span>
            </li>
            <li class="list-group-item d-flex justify-content-between lh-condensed">
              <div>
                <h6 class="my-0">Terceiro item</h6>
                <small class="text-muted">Breve descrição</small>
              </div>
              <span class="text-muted">R$5</span>
            </li>
            <li class="list-group-item d-flex justify-content-between bg-light">
              <div class="text-success">
                <h6 class="my-0">Código de promoção</h6>
                <small>CODIGOEXEMEPLO</small>
              </div>
              <span class="text-success">-R$5</span>
            </li>
            <li class="list-group-item d-flex justify-content-between">
              <span>Total (BRL)</span>
              <strong>R$20</strong>
            </li>
          </ul>

          <form class="card p-2">
            <div class="input-group">
              <input type="text" class="form-control" placeholder="Código promocional">
              <div class="input-group-append">
                <button type="submit" class="btn btn-secondary">Resgatar</button>
              </div>
            </div>
          </form>
        </div>
        <div class="col-md-8 order-md-1">
          <h4 class="mb-3">Endereço de cobrança</h4>
          <form class="needs-validation" novalidate>
            <div class="row">
              <div class="col-md-6 mb-3">
                <label for="primeiroNome">Nome</label>
                <input type="text" class="form-control" id="primeiroNome" placeholder="" value="" required>
                <div class="invalid-feedback">
                  É obrigatório inserir um nome válido.
                </div>
              </div>
              <div class="col-md-6 mb-3">
                <label for="sobrenome">Sobrenome</label>
                <input type="text" class="form-control" id="sobrenome" placeholder="" value="" required>
                <div class="invalid-feedback">
                  É obrigatório inserir um sobre nome válido.
                </div>
              </div>
            </div>

            <div class="mb-3">
              <label for="nickname">Nickname</label>
              <div class="input-group">
                <div class="input-group-prepend">
                  <span class="input-group-text">@</span>
                </div>
                <input type="text" class="form-control" id="nickname" placeholder="Nickname" required>
                <div class="invalid-feedback" style="width: 100%;">
                  Seu nickname é obrigatório.
                </div>
              </div>
            </div>

            <div class="mb-3">
              <label for="email">Email <span class="text-muted">(Opcional)</span></label>
              <input type="email" class="form-control" id="email" placeholder="fulano@exemplo.com">
              <div class="invalid-feedback">
                Por favor, insira um endereço de e-mail válido, para atualizações de entrega.
              </div>
            </div>

            <div class="mb-3">
              <label for="endereco">Endereço</label>
              <input type="text" class="form-control" id="endereco" placeholder="Rua dos bobos, nº 0" required>
              <div class="invalid-feedback">
                Por favor, insira seu endereço de entrega.
              </div>
            </div>

            <div class="mb-3">
              <label for="endereco2">Endereço 2 <span class="text-muted">(Opcional)</span></label>
              <input type="text" class="form-control" id="endereco2" placeholder="Apartamento ou casa">
            </div>

            <div class="row">
              <div class="col-md-5 mb-3">
                <label for="pais">País</label>
                <select class="custom-select d-block w-100" id="pais" required>
                  <option value="">Escolha...</option>
                  <option>Brasil</option>
                  <option>Argentina</option>
                  <option>Bolivia</option>
                  <option>EUA</option>
                  <option>Eapanha</option>
                  <option>Brahmas</option>
                  <option>França</option>
                  <option>Inglaterra</option>
                </select>
                <div class="invalid-feedback">
                  Por favor, escolha um país válido.
                </div>
              </div>
              <div class="col-md-4 mb-3">
                <label for="estado">Estado</label>
                <select class="custom-select d-block w-100" id="estado" required>
                  <option value="">Escolha...</option>
                  <option>MT</option>
                  <option>SP</option>
                  <option>RJ</option>
                  <option>GO</option>
                  <option>MTS</option>
                  <option>PR</option>
                  <option>TO</option>
                  <option>AM</option>
                </select>
                <div class="invalid-feedback">
                  Por favor, insira um estado válido.
                </div>
              </div>
              <div class="col-md-3 mb-3">
                <label for="cep">CEP</label>
                <input type="text" class="form-control" id="cep" placeholder="" required>
                <div class="invalid-feedback">
                  É obrigatório inserir um CEP.
                </div>
              </div>
            </div>
            <hr class="mb-4">
            <div class="custom-control custom-checkbox">
              <input type="checkbox" class="custom-control-input" id="mesmo-endereco">
              <label class="custom-control-label" for="mesmo-endereco">Endereço de entrega é o mesmo que o de cobrança.</label>
            </div>
            <div class="custom-control custom-checkbox">
              <input type="checkbox" class="custom-control-input" id="salvar-info">
              <label class="custom-control-label" for="salvar-info">Lembrar desta informação, na próxima vez.</label>
            </div>
            <hr class="mb-4">

            <h4 class="mb-3">Pagamento</h4>

            <div class="d-block my-3">
              <div class="custom-control custom-radio">
                <input id="credito" name="paymentMethod" type="radio" class="custom-control-input" checked required>
                <label class="custom-control-label" for="credito">Cartão de crédito</label>
              </div>
              <div class="custom-control custom-radio">
                <input id="debito" name="paymentMethod" type="radio" class="custom-control-input" required>
                <label class="custom-control-label" for="debito">Cartão de débito</label>
              </div>
              <div class="custom-control custom-radio">
                <input id="paypal" name="paymentMethod" type="radio" class="custom-control-input" required>
                <label class="custom-control-label" for="paypal">PayPal</label>
              </div>
            </div>
            <div class="row">
              <div class="col-md-6 mb-3">
                <label for="cc-nome">Nome no cartão</label>
                <input type="text" class="form-control" id="cc-nome" placeholder="" required>
                <small class="text-muted">Nome completo, como mostrado no cartão.</small>
                <div class="invalid-feedback">
                  O nome que está no cartão é obrigatório.
                </div>
              </div>
              <div class="col-md-6 mb-3">
                <label for="cc-numero">Número do cartão de crédito</label>
                <input type="text" class="form-control" id="cc-numero" placeholder="" required>
                <div class="invalid-feedback">
                  O número do cartão de crédito é obrigatório.
                </div>
              </div>
            </div>
            <div class="row">
              <div class="col-md-3 mb-3">
                <label for="cc-expiracao">Data de expiração</label>
                <input type="text" class="form-control" id="cc-expiracao" placeholder="" required>
                <div class="invalid-feedback">
                  Data de expiração é obrigatória.
                </div>
              </div>
              <div class="col-md-3 mb-3">
                <label for="cc-cvv">CVV</label>
                <input type="text" class="form-control" id="cc-cvv" placeholder="" required>
                <div class="invalid-feedback">
                  Código de segurança é obrigatório.
                </div>
              </div>
            </div>
            <hr class="mb-4">
            <button class="btn btn-primary btn-lg btn-block" type="submit">Continue o checkout</button>
          </form>
        </div>
      </div>

      <footer class="my-5 pt-5 text-muted text-center text-small">
        <p class="mb-1">&copy; 2021-2030 Nome da companhia</p>
        <ul class="list-inline">
          <li class="list-inline-item"><a href="#">Privacidade</a></li>
          <button name="button">Click me</button>
          <li class="list-inline-item"><a href="#">Termos</a></li>
          <button name="button">Click me</button>
          <li class="list-inline-item"><a href="#">Suporte</a></li
          >
        </ul>
      </footer>
    </div>
    <button name="button">Click me</button>
    
