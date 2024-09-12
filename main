public class Principal {


    public static void main(String[] args) {
        // matriz para resolução de sistema linear (Ax = b)
        double[] augmentedMatrixElements = {
                2,1,3,8,
                3,1,2,11,
                2,1,2,3
        };

        // matriz
        Matrix augmentedMatrix = new Matrix(3, 4, augmentedMatrixElements);

        System.out.println("\nMatriz inicial:");
        augmentedMatrix.mostrar();



        // resolvendo o sistema c gauss jordan
        Matrix solveMatrix = LinearAlgebra.solve(augmentedMatrix);

        System.out.println("\nMatriz resultante após Gauss-Jordan:");
        solveMatrix.mostrar();

        // Exemplo de multiplicação de matrizes
        double[] matrixAElements = {
                1,2,3,5,
                3,4,2,6,
                5,6,7,3,
                4,6,7,8,
        };
        double[] matrixBElements = {
                2,0,4,3,
                1,2,3,2,
                3,2,1,4,
                4,6,7,0,
        };

        Matrix matrixA = new Matrix(4, 4, matrixAElements);
        Matrix matrixB = new Matrix(4, 4, matrixBElements);

        System.out.println("\nMatriz A:");
        matrixA.mostrar();

        System.out.println("\nMatriz B:");
        matrixB.mostrar();

        Matrix product = LinearAlgebra.dot(matrixA, matrixB);

        System.out.println("\nProduto de A e B:");
        product.mostrar();

        // exemplo de matriz transposta
        Matrix transpostaA = LinearAlgebra.transpose(matrixA);

        System.out.println("\nMatriz A transposta:");
        transpostaA.mostrar();

        Matrix transpostaB = LinearAlgebra.transpose(matrixB);

        System.out.println("\nMatriz B transposta:");
        transpostaB.mostrar();

        // soma
        Matrix soma = LinearAlgebra.sum(matrixA, matrixB);
        System.out.println("\nSoma de A e B:");
        soma.mostrar();

        //  times
        Matrix times =  LinearAlgebra.times(matrixA, matrixB);
        System.out.println("\nMultiplicação termo a termo A e B:");
        times.mostrar();

       // multiplicação por escalar
        double scalar = 2.0;
        Matrix result = LinearAlgebra.times(matrixB, scalar);
        System.out.println("\nMatriz resultante da multiplicação por escalar " + scalar + ":");
        for (int i = 0; i < result.rows; i++) {
            for (int j = 0; j < result.cols; j++) {
                System.out.print(result.get(i, j) + " ");
            }
            System.out.println();
        }



    }
}

