<template>
<div class="privacy-politics">
    <div>
        <p id="privacy-politics-cookies">Política de privacidade • Aviso legal • Cookies</p>
    </div>
    <div id="cabreras-year-div">
        <!-- <svg xmlns="http://www.w3.org/2000/svg" width="16" height="" viewBox="0 0 16 16" fill="none">
        <path d="M1 8C1 11.866 4.13401 15 8 15C11.866 15 15 11.866 15 8C15 4.13401 11.866 1 8 1C4.13401 1 1 4.13401 1 8ZM16 8C16 12.4183 12.4183 16 8 16C3.58172 16 0 12.4183 0 8C0 3.58172 3.58172 0 8 0C12.4183 0 16 3.58172 16 8ZM8.14648 4.99219C6.93359 4.99219 6.21875 5.91211 6.21875 7.49414V8.55469C6.21875 10.125 6.92188 11.0156 8.14648 11.0156C9.125 11.0156 9.78711 10.4297 9.875 9.59766H11.1699V9.69141C11.0703 11.1387 9.81641 12.1582 8.14062 12.1582C6.04883 12.1582 4.87109 10.8223 4.87109 8.55469V7.48242C4.87109 5.2207 6.07227 3.84375 8.14062 3.84375C9.82227 3.84375 11.0762 4.89844 11.1699 6.41602V6.50391H9.875C9.78711 5.625 9.10742 4.99219 8.14648 4.99219Z" fill="#F0C986"/>
        </svg> -->
        <p id="cabreras-year">CABRERAs LTDA. 2024</p>       
    </div>     
</div>
</template>

<script>
export default {
    name: 'privacyPolitics',

}
</script>

<style>

.privacy-politics{
display: flex;
justify-content: center;
margin-top: 4.3438rem;
padding-bottom: 2.2563rem;
gap: 0.625rem;
}

#privacy-politics-cookies{
color: var(--clr-Beige-Light, #F0C986);

font-family: "Lexend Exa";
font-size: 1rem;
font-style: normal;
font-weight: 400;
line-height: normal;
}

#cabreras-year{
color: var(--clr-Beige-Light, #F0C986);

font-family: Lexend Exa;
font-size: 1rem;
font-style: normal;
font-weight: 400;
line-height: normal;
}

#cabreras-year-div{
display: flex;
justify-content: center;
align-items: center;
gap: 0.1875rem;
}

</style>