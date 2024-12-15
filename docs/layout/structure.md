<div class="header">
  <h1>Application de Dépannage</h1>
</div>
<div class="container">
  <div class="section">
    <h2>Signalement d'un Incident</h2>
    <form>
      <label for="incident-type">Type de panne</label>
      <select id="incident-type" name="incident-type" required>
        <option value="">-- Sélectionnez un type --</option>
        <option value="Plomberie">Plomberie</option>
        <option value="Électricité">Électricité</option>
        <option value="Chauffage">Chauffage</option>
        <option value="Autre">Autre</option>
      </select>
      <label for="incident-description">Description</label>
      <textarea id="incident-description" name="incident-description" rows="4" required></textarea>
      <button type="submit">Envoyer</button>
    </form>
  </div>
</div>


By default, the split pane view will show when the screen is larger than `768px`, or the `md` breakpoint, but this can be customized to use different breakpoints by setting the `when` property. Below is an example where the split pane contains a menu that is visible for `xs` screens and up, or when the viewport is larger than `0px`. This will show the split pane for all screen sizes.

It's important to note that the element with the `id` matching the `contentId` specified by the split pane will be the main content that is always visible. This can be any element, including a [nav](../api/nav.md), [router outlet](../api/router-outlet.md), or [tabs](../api/tabs.md).

import SplitPane from '@site/static/usage/v8/split-pane/basic/index.md';

<SplitPane />
