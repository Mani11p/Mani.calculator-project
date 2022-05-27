<template>
  <div>
  <table id="calculator" dir="ltr" style="text-align: center; margin: auto">
      <tr>
        <td colspan="5">
          <input
            v-model="screen"
            dir="ltr"
            id="result"
            type="number"
            style="padding: 5px; font-weight: bold; text-align: right"
          />