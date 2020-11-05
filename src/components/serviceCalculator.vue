<template>
    <div>
        <form action="">
            <div class="form-group row py-3">
                <div class="info-input col-2">
                    <span class="material-icons">emoji_objects</span>
                    <small class="d-block">Luz</small>
                </div>
                <div class="input-value col-10">
                    <div class="input-group mb-3">
                        <div class="input-group-prepend">
                            <span class="input-group-text">$</span>
                        </div>
                        <input type="number" class="form-control" aria-label="Dollar amount (with dot and two decimal places)">
                        <div class="input-group-append">
                            <button class="btn btn-outline-secondary" type="button" id="button-addon2">Cacular</button>
                        </div>
                    </div>
                    <div class="card text-white bg-primary mb-3">
                        <div class="card-header">Pago por Apartamento</div>
                        <div class="card-body">
                            <p class="card-text"><span class="material-icons">monetization_on</span><strong>40.000</strong></p>
                        </div>
                    </div>
                </div>
            </div>
            <div class="form-group row py-3">
                <div class="info-input col-2">
                    <span class="material-icons">opacity</span>
                    <small class="d-block">Agua</small>
                </div>
                <div class="input-value col-10">
                    <div class="input-group mb-3">
                        <div class="input-group-prepend">
                            <span class="input-group-text">$</span>
                        </div>
                        <input type="number" class="form-control" aria-label="Dollar amount (with dot and two decimal places)">
                        <div class="input-group-append">
                            <button class="btn btn-outline-secondary" type="button" id="button-addon2">Cacular</button>
                        </div>
                    </div>
                </div>
            </div>
            <div class="form-group row py-3">
                <div class="info-input col-2">
                    <span class="material-icons">fireplace</span>
                    <small class="d-block">Gas</small>
                </div>
                <div class="input-value col-10">
                    <div class="input-group mb-3">
                        <div class="input-group-prepend">
                            <span class="input-group-text">$</span>
                        </div>
                        <input type="number" class="form-control" aria-label="Dollar amount (with dot and two decimal places)">
                        <div class="input-group-append">
                            <button class="btn btn-outline-secondary" type="button" id="button-addon2">Cacular</button>
                        </div>
                    </div>
                </div>
            </div>
        </form>
    </div>
</template>
<script>
export default {
    name: 'serviceCalculator',
    data() {
        return {
            prueba: 123,
        }
    }
}
</script>