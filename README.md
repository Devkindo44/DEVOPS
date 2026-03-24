<form action="" method="POST" enctype="multipart/form-data">
            <h2>Inscrivez vous</h2>

            <div id="msgError"></div>

            <!--  -->
            <label for="pseudo">Pseudo</label>
            <input type="text" id="pseudo" name="pseudo" required placeholder="Saisissez votre pseudo" maxlength="10">

            <label for="">Mot de passe</label>
            <input type="password" id="password" name="password">

            <label for="">Email</label>
            <input type="email" id="email" name="email">

            <label for="cv">CV</label><br>
            <input type="file" name="cv" id="cv">

            <label for="pays">Pays</label><br>
            <select name="pays" id="pays">
                <option value="fr">France</option>
                <option value="es">Espagne</option>
                <option value="po">Portugal</option>
            </select>

            <label for="genre">Genre</label><br><br>
            <input type="radio" name="genre" id="genre" value="m">Homme
            <input type="radio" name="genre" id="genre" value="f">Femme
            <br>

            <label for="adresse">Adresse</label>
            <textarea name="adresse" id="adresse" rows="5"></textarea>
            <br>


            <!-- <input type="date" name="" id=""> -->
            <!-- <input type="range" name="" id=""> -->
             <!-- <input type="color" name="" id=""> -->

            <input type="submit" value="Valider">

        </form>

    </div>
</body>

</html>
