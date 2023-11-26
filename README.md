<style>
    @keyframes rotacion {
        0% {
            transform: rotate(0deg);
        }
        100% {
            transform: rotate(360deg);
        }
    }

    div {
        text-align: center;
    }

    div > img {
        border-radius: 0.625rem;
    }

    p {
        font-weight: bold;
    }

    table {
        width: 100%;
    }

    td {
        vertical-align: top;
        text-align: center;
    }

    td h3 {
        text-align: left;
    }

    #fila1 h2 {
        display: inline-block;
    }

    #tuerca {
        animation: rotacion 5s infinite linear;
        transform-origin: center;
        padding: 0;
    }
</style>

<div>
    <h1>Hi! I'm <a href="https://www.instagram.com/ander_vare/">Ander Varela</a> 👋</h1>
    <img src="https://i.imgur.com/vpcLELx.jpg" alt="Foto">
    <p>Aspiring software developer with solid programming knowledge and a strong interest in learning and growing in
        the field of computer engineering.</p>
    <table>
        <tr id="fila1">
            <td style="width: 40%;">
                <h2>🤪</h2>
                <h2>About me</h2>
            </td>
            <td style="width: 60%;">
                <h2 id="tuerca">⚙️</h2>
                <h2>GitHub Analytics</h2>
            </td>
        </tr>
        <tr>
            <td>
                <h3>- UDC student ✏️</h3>
                <h3>- Software developer 📲</h3>
            </td>
            <td>
                <img src="https://github-readme-stats-eight-theta.vercel.app/api?username=AnderVarela&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true"
                     alt="GitHub Stats"/>
            </td>
        </tr>
    </table>
</div>