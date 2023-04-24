# Documentación del código

## Clase NodoDoble
La clase `NodoDoble` representa un nodo de una lista doblemente enlazada. Tiene los siguientes atributos:
- `dato`: el valor almacenado en el nodo.
- `siguiente`: una referencia al siguiente nodo de la lista.
- `anterior`: una referencia al nodo anterior de la lista.

## Clase ListaDoble
La clase `ListaDoble` representa una lista doblemente enlazada. Tiene los siguientes atributos:
- `primero`: una referencia al primer nodo de la lista.
- `ultimo`: una referencia al último nodo de la lista.

La clase `ListaDoble` tiene los siguientes métodos:
- `agregar(dato)`: agrega un nuevo nodo al final de la lista, con el valor `dato`.
- `ordenar()`: ordena la lista usando el algoritmo de mezcla (`mergesort`).
- `_mergesort(head)`: implementa el algoritmo de mezcla recursivamente para ordenar la lista.
- `_get_middle(head)`: devuelve el nodo del medio de una lista, dividiéndola en dos mitades.
- `_merge(left, right)`: mezcla dos listas ordenadas y devuelve la lista resultante.
- `modificar(indice, nuevo_dato)`: modifica el valor de un nodo en la lista, dado su índice y un nuevo valor.
- `eliminar_repeticiones()`: elimina los nodos consecutivos que tienen el mismo valor en la lista.
- `eliminar_strings()`: elimina los nodos que contienen valores de tipo `str` en la lista.
- `eliminar(nodo)`: elimina un nodo dado de la lista.

## Clase de pruebas unitarias (TestListaDoble)
La clase `TestListaDoble` contiene pruebas unitarias para los métodos de la clase `ListaDoble`. Tiene los siguientes métodos de prueba:
- `setUp()`: prepara la instancia de la clase `ListaDoble` para las pruebas.
- `test_agregar_elementos()`: verifica que se agreguen correctamente varios elementos a la lista.
- `test_agregar_un_elemento()`: verifica que se agregue correctamente un elemento a la lista.
- `test_ordenar_lista_vacia()`: verifica que una lista vacía se ordene correctamente.
- `test_ordenar_lista_con_un_elemento()`: verifica que una lista con un solo elemento se ordene correctamente.
- `test_ordenar_lista_con_varios_elementos()`: verifica que una lista con varios elementos se ordene correctamente.
- `test_modificar_elemento_existente()`: verifica que se modifique correctamente un nodo existente en la lista.
