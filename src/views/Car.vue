<script setup>
import ListCompras from '@/components/ListCompras.vue';


</script>

<template>


<main>
<div class="container" style="max-width: 70rem; flex: auto; ">
    <div class="card border-card mb-3">
        <h5 class="card-title">Carrinho de Compras</h5>
        <div class="card-body text-dark">
            <div class="card-body" style="max-width: 66.5rem; flex: auto;">
                <div class="titulo">
                    <p class="produto"> Produto</p>
                    <p class="preco2">Preço</p>
                    <p class="quantidade">Quantidade</p>
                    <p class="x">-</p>
                </div>
                <hr class="linhe">
                <ol class="list-group list-group">
                    <li class="list-group-item d-flex justify-content-between align-items-start">
                    <img src="/public/favicon.ico" class="card-img-top" alt="...">
                    <div class="ms-2 me-auto">
                        <div class="fw-bold">Mouse Logitech Pro</div>
                             Content for list item
                        </div>
                        <div class="fw-bold" style="margin-right: 50%; margin: 10px;">R$ 540,00</div>
                       
                        <div class="input-groupe">
                            <div class="input-quant">
                                <button type="button" class="btn"
                                    style="--bs-btn-padding-y: .25rem; --bs-btn-padding-x: .5rem; --bs-btn-font-size: .75rem;">
                                <i class="pi pi-arrow-up" style="font-size: 1.0rem"></i>
                        </button>
                                <input v-text="msg" class="text-input" value= 1 style="width: 70px;">
                                <button type="button" class="btn "
                                    style="--bs-btn-padding-y: .25rem; --bs-btn-padding-x: .5rem; --bs-btn-font-size: .75rem;">
                                <i class="pi pi-arrow-down" style="font-size: 1.0rem"></i>
                        </button>
                            </div>
                        </div>
                        <button type="button" class="btn btn-danger"
                            style="--bs-btn-padding-y: .25rem; --bs-btn-padding-x: .5rem; --bs-btn-font-size: .75rem;">
                            <i class="pi pi-trash" style="font-size: 1.0rem"></i>
                        </button>
                    </li>
                    <br>
                </ol>
                <ol class="list-group list-group">
                    <li class="list-group-item d-flex justify-content-between align-items-start">
                    <img src="/public/favicon.ico" class="card-img-top" alt="...">
                    <div class="ms-2 me-auto">
                        <div class="fw-bold">Mouse Logitech Pro</div>
                             Content for list item
                        </div>
                        
                        <div class="input-groupe">
                            <div class="input-quant">
                                <button type="button" class="btn"
                                    style="--bs-btn-padding-y: .25rem; --bs-btn-padding-x: .5rem; --bs-btn-font-size: .75rem;">
                                <i class="pi pi-arrow-up" style="font-size: 1.0rem"></i>
                        </button>
                                <input v-text="msg" class="text-input" value= 1 style="width: 70px;">
                                <button type="button" class="btn "
                                    style="--bs-btn-padding-y: .25rem; --bs-btn-padding-x: .5rem; --bs-btn-font-size: .75rem;">
                                <i class="pi pi-arrow-down" style="font-size: 1.0rem"></i>
                        </button>
                            </div>
                        </div>
                        <button type="button" class="btn btn-danger"
                            style="--bs-btn-padding-y: .25rem; --bs-btn-padding-x: .5rem; --bs-btn-font-size: .75rem;">
                            <i class="pi pi-trash" style="font-size: 1.0rem"></i>
                        </button>
                    </li>
                    <br>
                </ol>
                <ol class="list-group list-group">
                    <li class="list-group-item d-flex justify-content-between align-items-start">
                    <img src="/public/favicon.ico" class="card-img-top" alt="...">
                    <div class="ms-2 me-auto">
                        <div class="fw-bold">Mouse Logitech Pro</div>
                             Content for list item
                        </div>
                        
                        <div class="input-groupe">
                            <div class="input-quant">
                                <button type="button" class="btn"
                                    style="--bs-btn-padding-y: .25rem; --bs-btn-padding-x: .5rem; --bs-btn-font-size: .75rem;">
                                <i class="pi pi-arrow-up" style="font-size: 1.0rem"></i>
                        </button>
                                <input v-text="msg" class="text-input" value= 1 style="width: 70px;">
                                <button type="button" class="btn "
                                    style="--bs-btn-padding-y: .25rem; --bs-btn-padding-x: .5rem; --bs-btn-font-size: .75rem;">
                                <i class="pi pi-arrow-down" style="font-size: 1.0rem"></i>
                        </button>
                            </div>
                        </div>
                        <button type="button" class="btn btn-danger"
                            style="--bs-btn-padding-y: .25rem; --bs-btn-padding-x: .5rem; --bs-btn-font-size: .75rem;">
                            <i class="pi pi-trash" style="font-size: 1.0rem"></i>
                        </button>
                    </li>
                    <br>
                </ol>
                <ol class="list-group list-group">
                    <li class="list-group-item d-flex justify-content-between align-items-start">
                    <img src="/public/favicon.ico" class="card-img-top" alt="...">
                    <div class="ms-2 me-auto">
                        <div class="fw-bold">Mouse Logitech Pro</div>
                             Content for list item
                        </div>
                        
                        <div class="input-groupe">
                            <div class="input-quant">
                                <button type="button" class="btn"
                                    style="--bs-btn-padding-y: .25rem; --bs-btn-padding-x: .5rem; --bs-btn-font-size: .75rem;">
                                <i class="pi pi-arrow-up" style="font-size: 1.0rem"></i>
                        </button>
                                <input v-text="msg" class="text-input" value= 1 style="width: 70px;">
                                <button type="button" class="btn "
                                    style="--bs-btn-padding-y: .25rem; --bs-btn-padding-x: .5rem; --bs-btn-font-size: .75rem;">
                                <i class="pi pi-arrow-down" style="font-size: 1.0rem"></i>
                        </button>
                            </div>
                        </div>
                        <button type="button" class="btn btn-danger"
                            style="--bs-btn-padding-y: .25rem; --bs-btn-padding-x: .5rem; --bs-btn-font-size: .75rem;">
                            <i class="pi pi-trash" style="font-size: 1.0rem"></i>
                        </button>
                    </li>
                    <br>
                </ol>
                <ol class="list-group list-group">
                    <li class="list-group-item d-flex justify-content-between align-items-start">
                    <img src="/public/favicon.ico" class="card-img-top" alt="...">
                    <div class="ms-2 me-auto">
                        <div class="fw-bold">Mouse Logitech Pro</div>
                             Content for list item
                        </div>
                        
                        <div class="input-groupe">
                            <div class="input-quant">
                                <button type="button" class="btn"
                                    style="--bs-btn-padding-y: .25rem; --bs-btn-padding-x: .5rem; --bs-btn-font-size: .75rem;">
                                <i class="pi pi-arrow-up" style="font-size: 1.0rem"></i>
                        </button>
                                <input v-text="msg" value= 1 class="text-input" style="width: 70px;">
                                <button type="button" class="btn "
                                    style="--bs-btn-padding-y: .25rem; --bs-btn-padding-x: .5rem; --bs-btn-font-size: .75rem;">
                                <i class="pi pi-arrow-down" style="font-size: 1.0rem"></i>
                        </button>
                            </div>
                        </div>
                        <button type="button" class="btn btn-danger"
                            style="--bs-btn-padding-y: .25rem; --bs-btn-padding-x: .5rem; --bs-btn-font-size: .75rem;">
                            <i class="pi pi-trash" style="font-size: 1.0rem"></i>
                        </button>
                    </li>
                    <br>
                </ol>
                
            </div>
        </div>
    </div>
</div>
</main>


</template>


<style>

.container{
  display: flex; 
  flex-wrap: wrap;
}

.card-img-top{
    width: 50px;
}

.form{
    width: 100px;
}
.text-input{
    text-align: center;
    border-radius: 10px;
    border-color: #DEE2E6;
    border-style: solid;
}
.list-group-item.d-flex.justify-content-between.align-items-start{
    border-color: white; 
}
.card.border-card.mb-3{
    border-color: white;
}
.linhe{
    line-height: 10rem;
}
.preco{
    margin-right: 12rem;
    font-size: 20px;
}

</style>