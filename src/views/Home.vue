<template>
  <div class="home">
    <h2>Testing Input Control</h2>

    <label for="margin-select">Choose your expected margin: </label>

    <select id="margin-select">
      <option value="">--Please choose an option--</option>
      <option value="20">20%</option>
      <option value="30">30%</option>
      <option value="40">40%</option>
      <option value="50">50%</option>
      <option value="60">60%</option>
    </select>

    <label for="project-cost">Enter estimated project cost: </label>
    <input id="project-cost" type="number" min="1" max="1000000" />
  </div>
</template>

