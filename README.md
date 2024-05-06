adicione align-items: center; porque não estava centralizando quando dimunia a pagina 

@media (max-width: 991px) {
    header {
        padding: 20px 50px;
        flex-direction: column;
        *align-items: center;
    }


ajustei o primeiro link para a o incone da lupa de pesquisa e do play 

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css" integrity="sha512-SnH5WK+bZxgPHs44uWIX+LLJAJ9/2PkPKZ5QiAj6Ta86w+fsb2TkcmfRyVX3pBnMFcV7oQPJkl9QevSCWr3W6A==" crossorigin="anonymous" referrerpolicy="no-referrer" />

referencia do canal = https://youtu.be/ghDnrZrMk_U

modifiquei top de 60% para 50%

.search .fa-search {
    position: absolute;
    *top: 50%;
    left: 10px;
    transform: translateY(-50%);
    padding-right: 50px;
    color: white;
    border-radius: 1px solid white;
}
