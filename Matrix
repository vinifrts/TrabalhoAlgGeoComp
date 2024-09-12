public class Matrix {
    public int rows, cols;
    private double[][] elements;

    // Construtor
    public Matrix(int rows, int cols, double[] elements) {
        this.rows = rows;
        this.cols = cols;
        this.elements = new double[rows][cols];

        for (int i = 0; i < rows; i++) {
            for (int j = 0; j < cols; j++) {
                this.elements[i][j] = elements[i * cols + j];
            }
        }
    }


    public double get(int i, int j) {
        return elements[i][j];
    }


    public void set(int i, int j, double value) {
        elements[i][j] = value;
    }

    // exibir a matriz
    public void mostrar() {
        for (int i = 0; i < rows; i++) {
            for (int j = 0; j < cols; j++) {
                System.out.print(elements[i][j] + " ");
            }
            System.out.println();
        }
    }

    // trocar duas linhas gauss
    public void swapRows(int row1, int row2) {
        double[] temp = elements[row1];
        elements[row1] = elements[row2];
        elements[row2] = temp;
    }
}
