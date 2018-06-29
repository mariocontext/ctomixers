<template>
  <span>
    <section>
      <div class="logo-area">
          <img src="~static/images/cto_mixers_logo_color_with_text_white@1x.png" alt="CTO Mixer text with graphics of drinking glasses">
      </div>
        <h1>General formatting - H1 Title Here</h1>
        <div class="section-bg-image">
          <span class="section-bg-image-caption">
            <p class="title is-3">Header image caption</p>
            <a class="button is-primary">Do this now</a>
          </span>
      </div>
    </section>

      <section>
        <h2>Subtitles - H2 Subtitle</h2>
        <p>Paragraph Lorem ipsum dolor sit amet consectetur adipisicing elit. <strong>example of strong text</strong> Mollitia odit commodi alias, laborum quidem laboriosam earum vero minima perspiciatis aut similique, eius consequuntur praesentium voluptate corporis, excepturi eveniet voluptates consectetur?</p>
        <p>Ipsam ipsa perferendis fuga excepturi dolores labore omnis sint, beatae <em>example of emphasised text</em> exercitationem repellendus officia aut rerum aspernatur <a href="#">example of linked text</a> laborum cumque numquam, tempore aliquid! Sint quia est laudantium qui adipisci voluptatibus unde itaque?</p>

        <h3>H3 subtitle</h3>
        <p>Ipsam ipsa perferendis fuga excepturi dolores labore omnis sint, beatae exercitationem repellendus officia aut rerum aspernatur laborum cumque numquam, tempore aliquid! Sint quia est laudantium qui adipisci voluptatibus unde itaque?</p>

        <h4>H4 Subtitle</h4>
        <p>Ipsam ipsa perferendis fuga excepturi dolores labore omnis sint, beatae exercitationem repellendus officia aut rerum aspernatur laborum cumque numquam, tempore aliquid! Sint quia est laudantium qui adipisci voluptatibus unde itaque?</p>

        <h5>H5 Subtitle</h5>
        <p>Ipsam ipsa perferendis fuga excepturi dolores labore omnis sint, beatae exercitationem repellendus officia aut rerum aspernatur laborum cumque numquam, tempore aliquid! Sint quia est laudantium qui adipisci voluptatibus unde itaque?</p>

    </section>

    <section>

      <h2>Lists</h2>

        <ul>
          <li>list item 1</li>
          <li>list item 2</li>
          <li>list item 3</li>
          <li>list item 4</li>
          <li>list item 5</li>
          <li>list item 6</li>
        </ul>

    </section>

    <section>
      <h2>Form elements</h2>

        <div class="field">
          <label class="label">Name</label>
          <div class="control">
            <input class="input" type="text" placeholder="Text input">
          </div>
        </div>

        <div class="field">
          <label class="label">Username</label>
          <div class="control has-icons-left has-icons-right">
            <input class="input is-success" type="text" placeholder="Text input" value="bulma">
            <span class="icon is-small is-left">
              <i class="fas fa-user"></i>
            </span>
            <span class="icon is-small is-right">
              <i class="fas fa-check"></i>
            </span>
          </div>
          <p class="help is-success">This username is available</p>
        </div>

        <div class="field">
          <label class="label">Email</label>
          <div class="control has-icons-left has-icons-right">
            <input class="input is-danger" type="email" placeholder="Email input" value="">
            <span class="icon is-small is-left">
              <i class="fas fa-envelope"></i>
            </span>
            <span class="icon is-small is-right">
              <i class="fas fa-exclamation-triangle"></i>
            </span>
          </div>
          <p class="help is-danger">This email is invalid</p>
        </div>

        <div class="field">
          <label class="label">Subject</label>
          <div class="control">
            <div class="select">
              <select>
                <option>Select dropdown</option>
                <option>With options</option>
              </select>
            </div>
          </div>
        </div>

        <div class="field">
          <label class="label">Message</label>
          <div class="control">
            <textarea class="textarea" placeholder="Textarea"></textarea>
          </div>
        </div>

        <div class="field">
          <div class="control">
            <label class="checkbox">
              <input type="checkbox">
              I agree to the <a href="#">terms and conditions</a>
            </label>
          </div>
        </div>

        <div class="field">
          <div class="control">
            <label class="radio">
              <input type="radio" name="question">
              Yes
            </label>
            <label class="radio">
              <input type="radio" name="question">
              No
            </label>
          </div>
        </div>

        <div class="field is-grouped">
          <div class="control">
            <button class="button is-link">Submit</button>
          </div>
          <div class="control">
            <button class="button is-text">Cancel</button>
          </div>
        </div>

    </section>

    <section class="button-examples-section">

      <h2>Buttons</h2>

      <h3>States</h3>

        <a class="button">Normal</a>
        <a class="button is-primary">Primary</a>
        <a class="button is-link">Link</a>
        <a class="button is-info">Info</a>
        <a class="button is-success">Success</a>
        <a class="button is-warning">Warning</a>
        <a class="button is-danger">Danger</a>
        <a class="button is-primary is-loading">Loading</a>
        <a class="button is-primary" title="Disabled button" disabled>Disabled</a>

      <h3>Inverted</h3>

        <a class="button is-primary is-inverted">Inverted</a>
        <a class="button is-link is-inverted">Inverted</a>
        <a class="button is-info is-inverted">Inverted</a>
        <a class="button is-success is-inverted">Inverted</a>
        <a class="button is-danger is-inverted">Inverted</a>

      <h3>Sizes</h3>

        <a class="button is-small">Small</a>
        <a class="button">Normal</a>
        <a class="button is-medium">Medium</a>
        <a class="button is-large">Large</a>
        

    </section>

    <section>

      <h2>Call to Actions</h2>

      <div class="call-to-action-area columns is-variable is-2">

        <div class="card call-to-action column is-one-third">
          <div class="card-image">
            <figure class="image is-4by3">
              <img src="https://bulma.io/images/placeholders/1280x960.png" alt="Placeholder image">
            </figure>
          </div>
          <div class="content">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit.
              Phasellus nec iaculis mauris. <a>@bulmaio</a>.
              <a href="#">#css</a> <a href="#">#responsive</a>
          </div>
          <footer class="card-footer">
              <a href="#" class="card-footer-item">Call to Action</a>
            </footer>
        </div>

        <div class="card call-to-action column is-one-third">
          <div class="card-image">
            <figure class="image is-4by3">
              <img src="https://bulma.io/images/placeholders/1280x960.png" alt="Placeholder image">
            </figure>
          </div>
          <div class="content">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit.
              Phasellus nec iaculis mauris. <a>@bulmaio</a>.
              <a href="#">#css</a> <a href="#">#responsive</a>
          </div>
          <footer class="card-footer">
              <a href="#" class="card-footer-item">Call to Action</a>
            </footer>
        </div>

        <div class="card call-to-action column is-one-third">
          <div class="card-image">
            <figure class="image is-4by3">
              <img src="https://bulma.io/images/placeholders/1280x960.png" alt="Placeholder image">
            </figure>
          </div>
          <div class="content">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit.
              Phasellus nec iaculis mauris. <a>@bulmaio</a>.
              <a href="#">#css</a> <a href="#">#responsive</a>
          </div>
          <footer class="card-footer">
              <a href="#" class="card-footer-item">Call to Action</a>
            </footer>
        </div>

      </div>

    </section>

  </span>
</template>

<script>

import IconCta from '~/components/IconCta.vue'

export default {

    components: {
      IconCta
    }

}

</script>

<style lang="scss" scoped>

.logo-area {
    max-width: 600px;
    margin: 0rem auto 3rem auto;
}

.logo-area,
.with-icons,
.my-centered-item
 {
  text-align: center;
}

.section-bg-image {
  height: 500px;
  background-image: url('~static/images/pexels-photo-696218.jpeg');
  background-size: cover;
  display: flex;
  justify-content: center;
  align-items: center;
  color: #FFF;
  margin: 0 -2rem;
  .section-bg-image-caption {
    display: flex;
    flex-direction: column;
    align-items: center;
    background: #000;
    padding: 1.5rem;
    background: rgba(0,0,0,0.85);
    .title {
      color: #FFF;
    }
  }
}

/* for stylguide layout presentation purposes only */

.button-examples-section .button {
  margin: 1rem;
}

/* cards */

.card.call-to-action.column {
    margin: 1rem .5rem;
    border-radius: 10px;
    .card-footer{
      border-top: none;
    }
}


</style>
