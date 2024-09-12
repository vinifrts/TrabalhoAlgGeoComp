public class Vector {

    private int dim;
    private double[] elements;


    public Vector(int dim, double[] elements) {
        if (elements.length == dim) {

            this.dim = dim;
            this.elements = elements;

        } else {
            System.out.println("o número de elementos não corresponde a dimensão");
        }
    }


    public double get(int i) {
        if (i < 0 || i >= dim) {
            System.out.println("Fora de intervalo");
        }
        return elements[i];
    }


    public void set(int i, double value) {
        if (i < 0 || i >= dim) {
            System.out.println("Fora de intervalo");
        }
        elements[i] = value;
    }


    public double[] getElements() {
        return elements;
    }


    public void setElements(double[] elements) {
        this.elements = elements;
    }
}
