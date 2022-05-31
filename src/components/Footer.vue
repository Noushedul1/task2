<template>
    <div class="container">
        <footer>
            <div>
                Social Link
                <ul>
                    <li>
                        <a href="https://www.facebook.com/noushedul.islam.71/" target="_blank">
                            <i class="fab fa-facebook fa-2x"></i>
                        </a>
                    </li>
                    <li>
                        <a href="https://github.com/Noushedul1" target="_blank">
                            <i class="fab fa-github fa-2x"></i>
                        </a>
                    </li>
                    <li>
                        <a href="https://www.linkedin.com/in/noushedul-islam-019609180/" target="_blank">
                        <i class="fab fa-linkedin fa-2x"></i>
                        </a>
                    </li>
                    <li>
                        <a href="">
                            noushedakib@gmail.com
                        </a>
                    </li>
                    <li>
                        <a href="">
                            01789773681
                        </a>
                    </li>
                </ul>
            </div>
            <div>
                <h4>
                    <strong>
                        Education
                    </strong>
                </h4>
                <ul>
                    <li v-for="edQu in educationQualififations" :key="edQu">
                        <a href="#">
                            {{edQu}}
                        </a>
                    </li>
                </ul>
            </div>
            <div>
                <h4>
                    <strong>
                        Address
                    </strong>
                </h4>
                <ul>
                    <li v-for="addr in address" :key="addr">
                        <a href="#">
                            {{addr}}
                        </a>
                    </li>
                </ul>
            </div>
        </footer>
    </div>
</template>
<script>
export default {
    data() {
        return {
            educationQualififations : [
                 'Mirzar hat high school',
                 'fatickchari College',
                 'Southern University'
            ],
            address: [
                    'Village - Idilpur',
                    'Upazila - Fatickchari',
                    'Division -Chattogram',
                    'City - Chattogram',
                    'country -Bangladesh'
            ]
        }
    }
}
</script>
<style scoped>
footer{
    display: flex;
    justify-content: space-around;
    flex-wrap: wrap;
}
footer li{
    list-style-type: none;
}
a{
    text-decoration: none;
}
</style>
