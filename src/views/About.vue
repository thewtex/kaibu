<template>
  <div class="about">
    <section
      class="hero"
      style="max-width: 100%; width: 600px; text-align: center; margin-left: auto;
  margin-right: auto;"
    >
      <div class="hero-body">
        <div class="container">
          <h1 class="title">About Kaibu</h1>
          <h2 class="subtitle">v{{ version }}</h2>
          <p>
            Kaibu is a web application for visualizing and annotating
            multi-dimensional images, built with
            <a href="https://openlayers.org/" target="_blank" rel="nofollow"
              >OpenLayers</a
            >
            and
            <a
              href="https://kitware.github.io/itk-vtk-viewer/"
              target="_blank"
              rel="nofollow"
              >itk-vtk-viewer</a
            >.
          </p>
          <br />
          <h2 class="subtitle">Why Kaibu?</h2>
          <p>
            <code>Kaibu</code> is
            <a
              href="https://www.google.com/maps/place/Kaibu+Island/"
              rel="nofollow"
              target="_blank"
              >a small island in Fiji</a
            >, and we name it to pay tribute to the open source image processing
            package <a href="https://fiji.sc/" rel="nofollow">Fiji</a>/<a
              href="https://imagej.net"
              rel="nofollow"
              target="_blank"
              >ImageJ</a
            >. Meanwhile, the layered design of Kaibu is inspired by
            <a href="https://napari.org/" target="_blank" rel="nofollow"
              >Napari</a
            >
            which is also named after an island. <code>Kaibu</code> in
            Chinese(开步), it means "to step forward", and yes, it is time to
            step forward with Kaibu!
          </p>
          <p>
            <a
              target="_blank"
              rel="noopener noreferrer"
              href="https://raw.githubusercontent.com/imjoy-team/kaibu/master/public/static/img/kaibu-logo.gif?sanitize=true"
              ><img
                src="https://raw.githubusercontent.com/imjoy-team/kaibu/master/public/static/img/kaibu-logo.gif?sanitize=true"
                width="400"
                alt="Kaibu"
                style="max-width:100%;"
            /></a>
          </p>
        </div>
      </div>
    </section>
  </div>
</template>
<script>
import { version } from "../../package.json";
export default {
  name: "About",
  data() {
    return {
      version
    };
  }
};
</script>
