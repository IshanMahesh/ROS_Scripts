import sympy as sym
phi, psi, theta, cos, sin = symsymbols('phi, psi, theta, cos, sin')

def Rotation_Matrix(theta, phi, psi)
    Rx = sym.Matrix ([[ 1, 0, 0],
                      [ 0, cos(phi), -sin(phi)],
                      [ 0, sin(phi), cos(phi)]])
    
    Ry = sym.Matrix ([[ cos(theta), 0, sin(theta)],
                      [ 0, 1, 0],
                      [ -sin(theta) , 0, cos(theta)]])
                      
    Rz = sym.Matrix ([[ cos(psi), -sin(psi), 0],
                      [ sin(psi), cos(psi), 0],
                      [ 0, 0, 1]])
                      
R = Rz*Ry*Rx
R = sym.simpify(R)
