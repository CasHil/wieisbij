<template>
  <div class="accordion-wrapper">
    <div class="accordion" role="tablist">
      <b-card no-body class="mb-1">
        <b-card-header header-tag="header" class="p-1" role="tab">
          <b-button block v-b-toggle.accordion-1 variant="info"
            >Wat is dit?</b-button
          >
        </b-card-header>
        <b-collapse
          id="accordion-1"
          visible
          accordion="my-accordion"
          role="tabpanel"
        >
          <b-card-body>
            <b-card-text
              >Dit is "Wie is bij?", een website die ik ben begonnen om snel te
              kunnen polsen wie er allemaal bij een feestje, borrel of ander
              evenement is. Zo hoef je je groepschat niet vol te spammen met
              berichten en heb je een makkelijk overzicht.</b-card-text
            >
          </b-card-body>
        </b-collapse>
      </b-card>

      <b-card no-body class="mb-1">
        <b-card-header header-tag="header" class="p-1" role="tab">
          <b-button block v-b-toggle.accordion-2 variant="info"
            >Hoe werkt het?</b-button
          >
        </b-card-header>
        <b-collapse id="accordion-2" accordion="my-accordion" role="tabpanel">
          <b-card-body>
            <b-card-text
              >Een persoon maakt een "bijtje" aan en kan het linkje doorsturen
              naar alle uitgenodigden. Deze persoon kan dan aangeven of die
              erbij zal zijn.</b-card-text
            >
          </b-card-body>
        </b-collapse>
      </b-card>

      <b-card no-body class="mb-1">
        <b-card-header header-tag="header" class="p-1" role="tab">
          <b-button block v-b-toggle.accordion-3 variant="info"
            >Accordion 3</b-button
          >
        </b-card-header>
        <b-collapse id="accordion-3" accordion="my-accordion" role="tabpanel">
          <b-card-body>
            <b-card-text>
              Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aliquid
              nam nulla dolore eveniet, quis doloremque nostrum laudantium quae
              sapiente, itaque possimus culpa molestiae iure, alias et ipsum
              voluptatem? Doloremque, voluptas!</b-card-text
            >
          </b-card-body>
        </b-collapse>
      </b-card>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.accordion-wrapper {
  margin: 0 auto;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  padding: 1rem 1rem;
}

.accordion {
  margin: 0 auto;
  width: 50%;
}

.btn-info {
  background-color: $honey-yellow;
  border-color: $bee-yellow;
}

.card-body {
  background-color: $bee-yellow;
}

.card-header {
  background-color: $bee-yellow;
}

.accordion > .card {
  margin: 0.5rem 0;
}
</style>
