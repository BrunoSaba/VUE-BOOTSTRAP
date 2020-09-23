<template>
<div class="container">
        <div class="col-sm-12">
            <h1>Últimos Projetos</h1>
            <div class="tableone ">
            <b-table :items="items" :fields="fields" :tbody-tr-class="rowClass" :fields-variant="light"></b-table>
            </div>
        </div>
</div>
</template>

<script>
  export default {
    data() {
      return {
        fields: ['Nome_do_Projeto', 'Data_de_Inicio', 'Data_de_Finalização', 'status', 'ações'],
        items: [
          { Nome_do_Projeto: 'Projeto-1', Data_de_Inicio: '13/06/2016', Data_de_Finalização: '13/08/2016' , status: 'Captura', ações: '' },
          { Nome_do_Projeto: 'Projeto-2', Data_de_Inicio: '13/06/2016', Data_de_Finalização: '13/08/2016', status: 'Tratamento', ações: '' },
          { Nome_do_Projeto: 'Projeto-3', Data_de_Inicio: '13/06/2016', Data_de_Finalização: '13/08/2016', status: 'Aprovação', ações: '' },
          { Nome_do_Projeto: 'Projeto-4', Data_de_Inicio: '13/06/2016', Data_de_Finalização: '13/08/2016', status: 'Concluído', ações: '' },
          { Nome_do_Projeto: 'Projeto-5', Data_de_Inicio: '13/06/2016', Data_de_Finalização: '13/08/2016', status: 'Concluído', ações: '' },
          
        ]
      }
    },
    methods: {
      rowClass(item, type) {
        if (!item || type !== 'row') return
        if (item.status === 'awesome') return 'table-success'
      }
    }
  }
</script>

<style>
 h1, .h1 {
   float: left;
 }
</style>