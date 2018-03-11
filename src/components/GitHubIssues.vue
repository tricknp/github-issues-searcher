<template>
    <div class="container">
        
        <form action="" class="form">
            <div class="square">
                <div class="inputs">
                    <input type="text" id="" placeholder="github username">
                    <input type="text" id="" placeholder="github repository">
                </div>

                <div class="buttons">
                    <button>Search</button>
                    <button>Clear</button>
                </div>
            </div>    
        </form>   

        <table class="">
            <thead>
                <tr>
                    <th width="100">Número</th>
                    <th>Título</th>
                </tr>
            </thead>

            <tbody>
                <tr>
                    <td class="text-center" colspan="2">Nenhuma issues encontrada!</td>
                </tr>
            </tbody>
        </table>
               
    </div>
</template>

<script>
export default {
  name: 'GitHubIssues',

  data(){
      return{

      };
  },

  methods: {},

}
</script>
