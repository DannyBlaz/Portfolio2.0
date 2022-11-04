<article class="card">
        <header class="card-header">
          <p>Sep 11th 2020</p>
          <h2>Card Tricks are fun!</h2>
        </header>

        <div class="card-author">
          <a class="author-avatar" href="#">
            <img src="https://api.adorable.io/avatars/172/a.png" />
          </a>
          <svg class="half-circle" viewBox="0 0 106 57">
            <path d="M102 4c0 27.1-21.9 49-49 49S4 31.1 4 4"></path>
          </svg>

          <div class="author-name">
            <div class="author-name-prefix">Pirate</div>
            Zheng Zhilong
          </div>
        </div>
        <div class="tags">
          <a href="#">html</a>
          <a href="#">css</a>
        </div>
      </article>


      <h2>My projects</h2>
                <ul>
                    <div>
                        <h3>FineArt</h3>
                        <img src="/Users/danielezekiel/Documents/my_website/Portfolio2.0/static/gifs/6zb28w.gif" alt="FineArt">
                        <li>Utilized Session and localStorage to store encrypted user information client-side.</li>
                        <li>Introduced Heroku to provide web access</li>
                        <li>Included Bcrypt for Authentication</li>
                        <li>Honed my skills in building my CSS from scratch</li>
                    </div>
                    <div>
                        <h3>Message Board</h3>
                        <img src="/Users/danielezekiel/Documents/my_website/Portfolio2.0/static/gifs/6zawvr.gif" alt="Girl in a jacket">
                        <li>Wrote Authentication for the User model, User controller, and Sessions controller</li>
                        <li>Used Rails Active_model_serializer to reduce the number of fetches made</li>
                        <li>Wrote reusable code in Ruby for the Model and Controller</li>
                        <li>Completed the MVC frame with JavaScript React components for Views</li>
                    </div>
                    <div>
                        <h3>Texas Destinations</h3>
                        <img src="/Users/danielezekiel/Documents/my_website/Portfolio2.0/static/gifs/6zb2mc.gif" alt="Halloween">
                        <li>Introduced Bootstrap to establish a more responsive web app</li>
                        <li>Worked using REST APIs to fetch data</li>
                        <li>Used Switch from React-Router-Dom to switch between client-side routes</li>
                        <li>Utilize Carousel form React-Bootstrap to switch images on the home page</li>
                    </div>
                </ul>

                #projects ul{
    display: flex;
}

#projects ul div{
    display: flex;
    flex-direction: column;
    background-color: blue;
    height: 700px;
    width: 300px;
}

img{
    height: 300px;
    width: 300px
}