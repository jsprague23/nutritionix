<template>

    <div class="container foodDetails">
        <div class="row">
            <h1>FOOD DETAILS</h1>
        </div>

        <div class="row">
            <div class="col-12">
                <h3>NAME:</h3>
                <ol>
                    <li>{{item.foods.food_name}}</li>
                    <li>{{item.foods.nf_calories}</li>
                    <li>{{item.foods.nf_total_carbohydrate}</li>
                    <li>{{item.foods.nf_protein}</li>
                </ol>
            </div>
        </div>
    </div>

    </div>
</template>


<script>
    export default {
        name: 'FoodDetails',
        data() {
            return {
                foods
            }
        }
    }
</script>









<style scoped>
</style>