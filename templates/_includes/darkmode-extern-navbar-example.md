For _Design Communication_, the darkmode switch should be inside _accessibility component_ with others switches. This navbar example contains a working link, try it now !

<div class="bd-example">
  <div class="mastheader" data-component="mastheader">
    <div class="container">
      <header role="banner" class="d-flex align-items-center">
        <div class="mastheader-logo">
          <a href="/docs" class="d-block">
            <img alt="" class="d-block" src="/assets/img/brand/sncf-logo.png" width="34" />
          </a>
        </div>
        <h1 class="mastheader-title flex-fluid text-white">Les trains en Ile-de-France de SNCF</h1>
      </header>
      <ul class="mastheader-toolbar mb-0 d-none d-md-flex">
        <li class="mastheader-toolbar-item dropdown dropdown-mastheader">
          <button type="button" class="dropdown-toggle" data-toggle="dropdown" data-offset="68, 0" aria-haspopup="true" aria-expanded="false">Accessibilité <i class="icons-arrow-down icons-size-x5 ml-2" aria-hidden="true"></i></button>
          <div class="dropdown-menu dropdown-menu-right">
            <i class="dropdown-close icons-close icons-size-x5"></i>
            <div data-role="stop-propagation">
              <div class="mb-3">
                <label class="w-100 text-white font-weight-medium mb-2">Mode sombre</label>
                <div class="options-control options-control-lg">
                  <div class="options-item">
                    <input type="radio" name="darkmode" id="darkmode-disabled" class="sr-only" checked/>
                    <label class="darkmode-btn options-btn font-weight-medium" for="darkmode-disabled">Désactivé</label>
                  </div>
                  <div class="options-item">
                    <input type="radio" name="darkmode" id="darkmode-active" class="sr-only"/>
                    <label class="darkmode-btn options-btn font-weight-medium" for="darkmode-active">Activé</label>
                  </div>
                </div>
              </div>
              <div class="mb-3">
                <label class="w-100 text-white font-weight-medium mb-2">Police (dyslexie)</label>
                <div class="options-control options-control-lg">
                  <div class="options-item">
                    <input type="radio" name="typography" id="typography-default" class="sr-only" checked/>
                    <label class="options-btn font-weight-medium" for="typography-default">Défaut</label>
                  </div>
                  <div class="options-item">
                    <input type="radio" name="typography" id="typography-adapted" class="sr-only"/>
                    <label class="options-btn font-weight-medium" for="typography-adapted">Adaptée</label>
                  </div>
                </div>
              </div>
              <div class="mb-3">
                <label class="w-100 text-white font-weight-medium mb-2">Contrastes</label>
                <div class="options-control options-control-lg">
                  <div class="options-item">
                    <input type="radio" name="contrast" id="contrast-default" class="sr-only" checked/>
                    <label class="options-btn font-weight-medium" for="contrast-default">Défaut</label>
                  </div>
                  <div class="options-item">
                    <input type="radio" name="contrast" id="contrast-strong" class="sr-only"/>
                    <label class="options-btn font-weight-medium" for="contrast-strong">Renforcés</label>
                  </div>
                  <div class="options-item">
                    <input type="radio" name="contrast" id="contrast-inverted" class="sr-only"/>
                    <label class="options-btn font-weight-medium" for="contrast-inverted">Inversés</label>
                  </div>
                </div>
              </div>
              <div class="mb-3">
                <label class="w-100 text-white font-weight-medium mb-2">Interlignage</label>
                <div class="options-control options-control-lg">
                  <div class="options-item">
                    <input type="radio" name="lineheight" id="lineheight-default" class="sr-only" checked/>
                    <label class="options-btn font-weight-medium" for="lineheight-default">Défaut</label>
                  </div>
                  <div class="options-item">
                    <input type="radio" name="lineheight" id="lineheight-increases" class="sr-only"/>
                    <label class="options-btn font-weight-medium" for="lineheight-increases">Augmenté</label>
                  </div>
                </div>
              </div>
              <div>
                <label class="w-100 text-white font-weight-medium mb-2">Animations</label>
                <div class="options-control options-control-lg">
                  <div class="options-item">
                    <input type="radio" name="animations" id="enabled" class="sr-only" checked/>
                    <label class="options-btn font-weight-medium" for="enabled">Option 1</label>
                  </div>
                  <div class="options-item">
                    <input type="radio" name="animations" id="disabled" class="sr-only"/>
                    <label class="options-btn font-weight-medium" for="disabled">Option 2</label>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </li>
        <li class="mastheader-toolbar-item dropdown dropdown-mastheader dropdown-lang">
          <button type="button" class="dropdown-toggle" data-toggle="dropdown" data-offset="52, 0" aria-haspopup="true" aria-expanded="false">Langue : Fr <i class="icons-arrow-down icons-size-x5 ml-2"></i></button>
          <div class="dropdown-menu dropdown-menu-right">
            <i class="dropdown-close icons-close icons-size-6px"></i>
            <div class="pr-5">
              <div class="dropdown-menu-lang-item active">
                <img src="https://dummyimage.com/30x30/000/fff" alt="Drapeaux Français" class="gr-3" />
                Français
              </div>
              <div class="dropdown-menu-lang-item">
                <img src="https://dummyimage.com/30x30/000/fff" alt="Drapeaux Anglais" class="gr-3" />
                English
              </div>
              <div class="dropdown-menu-lang-item">
                <img src="https://dummyimage.com/30x30/000/fff" alt="Drapeaux Allemand" class="gr-3" />
                Deutsch
              </div>
            </div>
          </div>
        </li>
        <li class="mastheader-toolbar-item mastheader-toolbar-item-lg">
          <button type="button">Tout sncf <i class="icons-options ml-3" aria-hidden="true"></i></button>
        </li>
      </ul>
    </div>
  </div>
</div>
