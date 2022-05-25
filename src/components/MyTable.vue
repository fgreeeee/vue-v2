<template>
      <table class="table">
        <thead>
        <tr>
          <th scope="col">#</th>
          <th scope="col">First</th>
          <th scope="col">Last</th>
          <th scope="col">Handle</th>
          <th scope="col">Number</th>
        </tr>
        </thead>
        <tbody>
        <tr>
          <th scope="row">1</th>
          <td>Mark</td>
          <td>Otto</td>
          <td>@mdo</td>
          <td>+7 (908) 777-52-54</td>
        </tr>
        <tr>
          <th scope="row">2</th>
          <td>Jacob</td>
          <td>Thornton</td>
          <td>@fat</td>
          <td>+7 (921) 695-54-95</td>
        </tr>
        <tr>
          <th scope="row">3</th>
          <td>Larry the Bird</td>
          <td>@ters</td>
          <td>@twitter</td>
          <td>+7 (908) 777-52-54</td>
        </tr>
        <tr>
          <th scope="row">4</th>
          <td>Vova</td>
          <td>Otto</td>
          <td>@mdo</td>
          <td>+7 (908) 777-52-54</td>
        </tr>
        <tr>
          <th scope="row">1</th>
          <td>Ref</td>
          <td>Otto</td>
          <td>@mdo</td>
          <td>+7 (948) 453-42-74</td>
        </tr>
        <tr>
          <th scope="row">1</th>
          <td>Mark</td>
          <td>Otto</td>
          <td>@mdo</td>
          <td>+7 (995) 311-16-66</td>
        </tr>
        </tbody>
      </table>

</template>

<script>

export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<style scoped>

</style>