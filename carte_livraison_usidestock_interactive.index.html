<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>USIDESTOCK - Calculateur de Tarifs de Livraison</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
            padding: 0;
            background-image: url('https://zupimages.net/up/24/39/w974.jpg'); /https://zupimages.net/up/24/39/w974.jpg/
            background-size: cover;
            background-position: center;
            background-repeat: no-repeat;
            background-attachment: fixed;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
            border: 1px solid #205285;
            border-radius: 20px;
            background-color: rgba(255, 255, 255, 1);
            box-shadow: 0 0 20px rgba(0, 0, 0, 1);
        }
        h2 {
            text-align: center;
        }
        .result {
            margin-top: 30px;
            font-weight: bold;
        }
    </style>
</head>
<body>
    <div class="container">
        <h2>USIDESTOCK - Calculateur de Tarifs de Livraison</h2>
        <label for="ville">Sélectionnez la ville :</label>
        <select id="ville"></select>
        <br><br>
        <label for="livraison">Type de livraison :</label>
        <select id="livraison">
            <option value="camion">livraison devant le camion</option>
            <option value="piece">livraison dans la pièce de votre choix</option>
        </select>
        <br><br>
        <button onclick="calculerTarif()">Calculer le tarif</button>

        <div class="result" id="resultat"></div>
    </div>

    <script>
        // Liste des villes avec les distances en kilomètres par rapport à Crosville-la-Vieille
        const distances = {
            "Villez sur le Neubourg": 4,
            "Crestot": 7,
            "Ecquetot": 7,
            "Feuguerolles": 10,
            "Ste opportune du bosc": 6,
            "Le tremblay omonville": 4,
            "Le troncq": 4,
            "Villettes": 9,
            "Venon": 10,
            "Vitot": 1.5,
            "Crosville la vieille": 0,
            "Ecauville": 6.5,
            "Iville": 3,
            "Criquebeuf la campagne": 8,
            "Epegard": 4,
            "Le neubourg": 1,
            "Quittebeuf": 9,
            "Rouge perriers": 6,
            "St aubin d ecrosville": 6,
            "Le tilleul lambert": 8,
            "Berengeville la campagne": 12,
            "Cesseville": 5,
            "Daubeuf la campagne": 9,
            "Epreville pres le neubourg": 4,
            "Marbeuf": 4,
            "Ste colombe la commanderie": 6,
            "Graveron semerville": 8,
            "Hectomare": 5,
            "Tourville la campagne": 8,
            "Le bosc du theil": 10,
            "Le thuit de l oison": 12,
            "Vraiville": 12,
            "St ouen de pontcheuil": 10,
            "St pierre des fleurs": 11,
            "St pierre du bosguerard": 12,
            "La saussaye": 10.14,
            "St meslin du bosc": 10.14,
            "Amfreville st amand": 10.14,
            "La haye du theil": 10.14,
            "Mandeville": 10.14,
            "La pyle": 10.14,
            "St didier des bois": 10.14,
            "Le bec thomas": 10.14,
            "Fouqueville": 10.14,
            "La harengere": 10.14,
            "St cyr la campagne": 10.14,
            "Houlbec pres le gros theil": 10.14,
            "St germain de pasquier": 10.14,
            "Bosnormand": 16.47,
            "St ouen du tilleul": 16.47,
            "Le bosc roger en roumois": 16.47,
            "La neuville du bosc": 16.69,
            "St pierre les elbeuf": 17.27,
            "Caudebec les elbeuf": 17.27,
            "Ecardenville la campagne": 17.90,
            "Le tilleul othon": 17.90,
            "Tilleul dame agnes": 17.90,
            "Beaumontel": 17.90,
            "Beaumont le roger": 17.90,
            "Berville la campagne": 17.90,
            "Bray": 17.90,
            "Grosley sur risle": 17.90,
            "Combon": 17.90,
            "Le plessis ste opportune": 17.90,
            "Barc": 17.90,
            "Barquet": 17.90,
            "Perriers la campagne": 17.90,
            "Romilly la puthenaye": 17.90,
            "Goupillieres": 17.90,
            "Elbeuf": 17.94,
            "Orival": 17.94,
            "La londe": 17.94,
            "Louviers": 20.58, 
            "Vironvay": 20.58,
            "Montaure": 20.58,
            "Pinterville": 20.58,
            "Canappeville": 20.58,
            "Incarville": 20.58,
            "Le mesnil jourdain": 20.58,
        };

        // Générer le menu déroulant des villes
        function genererMenuVilles() {
            const villeSelect = document.getElementById("ville");
            const villes = Object.keys(distances).sort(); // Trier les villes par ordre alphabétique

            villes.forEach(ville => {
                const option = document.createElement("option");
                option.value = ville;
                option.textContent = ville;
                villeSelect.appendChild(option);
            });
        }

        function calculerTarif() {
            const ville = document.getElementById("ville").value;
            const livraison = document.getElementById("livraison").value;

            // Vérifier si la ville est dans la liste
            if (distances[ville] !== undefined) {
                const distance = distances[ville];
                let tarif = 0;

                // Déterminer le tarif en fonction de la distance et du type de livraison
                if (distance <= 10) {
                    tarif = livraison === "camion" ? 25 : 39;
                } else if (distance > 10 && distance <= 30) {
                    tarif = livraison === "camion" ? 35 : 49;
                } else {
                    document.getElementById("resultat").innerText = "La livraison pour cette distance n'est pas disponible.";
                    return;
                }

                // Afficher le résultat
                document.getElementById("resultat").innerText = `La livraison à ${ville} (${distance} km) coûte ${tarif} euros pour une livraison ${livraison === "camion" ? "devant le camion" : "dans la pièce de votre choix"}.`;
            } else {
                document.getElementById("resultat").innerText = "Désolé, la ville sélectionnée n'est pas dans la liste des villes disponibles.";
            }
        }

        // Générer le menu des villes lorsque la page est chargée
        window.onload = genererMenuVilles;
    </script>
</body>
</html>
