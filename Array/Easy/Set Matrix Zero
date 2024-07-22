class Solution(object):
    def setZeroes(self, matrix):
        """
        :type matrix: List[List[int]]
        :rtype: None Do not return anything, modify matrix in-place instead.
        """
        l=[] 
        for i in range(len(matrix)):
            for j in range(len(matrix[i])):
                if matrix[i][j]== 0:
                    l.append(j)
        
        for i in range(len(matrix)):
            if 0 in matrix[i]:
                for k in range(len(matrix[i])):
                    matrix[i][k]=0
            else:
                for m in l:
                    matrix[i][m]=0

        return matrix


        
