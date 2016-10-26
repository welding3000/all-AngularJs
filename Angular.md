# Angular

// Angular aplicar codigo

    angular.module('contenedor',[])
      .controller('pera',
        function($scope){
// Crear un array

    $scope.alumnos=[
     {nombre:'Juan'},
     {nombre:'Pablo'},
     {nombre:'Cristian'},
     {nombre:'Escobar'},
     {nombre:'Peres'},
     {nombre:'Michael'}
    ];
//  Guardar un Objetivo

    $scope.Save=function(){
     $scope.alumnos.push({ 
       nombre:$scope.nuevoAlumno.nombre,
       });    
    };
//Buscar un objetivo

    $scope.friends=[
      {name:'John'},
      {name:'Mary'},
      {name:'Mike'},
      {name:'Adam'},
      {name:'Julie'},
      {name:'Juliette'}
     ];   
    });
