# Pimienta-Castillo-Kevin
Investigacion
Cola(Queue):
             Métodos más comunes: Enqueue, Dequeue (devuelve y elimina la cabeza de la cola).
             Es una estructura FIFO (first in, first out), el primero en entrar es el primero en salir.

            Queue<string> cola = new Queue<string>();cola.Enqueue(“1”); cola.Enqueue(“2”); cola.Enqueue(“3”);
            foreach(double x in cola) Console.WriteLine(x);
            while (cola.Count > 0) Console.WriteLine(cola.Dequeue());

            Cola
            Insertar: almacena al final de la cola el elemento que se recibe como parámetro. 
            Eliminar: Saca de la cola el elemento que se encuentra al frente.


             Pila(Stack):
             Métodos más comunes: Push, Pop (devuelve y elimina el top).
             Es una estructura LIFO (last in, first out), el último que entra es el primero en salir.

            Stack<double> pila = new Stack<double>();pila.Push(3.141); pila.Push(3.1415); pila.Push(3.14159);
            foreach(double x in pila) Console.WriteLine(x);
            while (pila.Count > 0) Console.WriteLine(pila.Pop());

            Pila:
            PUSH (insertar): Agrega un elemento a la pila en el extremo llamado tope. 
            POP (remover): Remueve el elemento de la pila que se encuentra en el extremo llamado tope. 
