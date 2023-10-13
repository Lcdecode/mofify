if (x_circulo1 - x_circulo2)**2 + (y_circulo1 - y_circulo2)**2 <= (radio1 + radio2)**2:
            if colision_detectada:
                colision_detectada = True  # Marcar que se ha detectado una colisión
                if color_circulo1 == BombAz:
                    color_circulo1 = CircleAz
                    if color_circulo2 == CircleAz
                        color_circulo2 = BombAz
                    elif  color_circulo2 == CircleRo
                        color_circulo2 = BombRo
                    elif  color_circulo2 == CircleVe
                        color_circulo2 = BombVe
                    elif  color_circulo2 == CircleAm
                        color_circulo2 = BombAm
                elif color_circulo1 == BombRo:
                    color_circulo1 = CircleRo
                    if color_circulo2 == CircleAz
                        color_circulo2 = BombAz
                    elif  color_circulo2 == CircleRo
                        color_circulo2 = BombRo
                    elif  color_circulo2 == CircleVe
                        color_circulo2 = BombVe
                    elif  color_circulo2 == CircleAm
                        color_circulo2 = BombAm
                elif color_circulo1 == BombVr:
                    color_circulo1 = CircleVe
                    if color_circulo2 == CircleAz
                        color_circulo2 = BombAz
                    elif  color_circulo2 == CircleRo
                        color_circulo2 = BombRo
                    elif  color_circulo2 == CircleVe
                        color_circulo2 = BombVe
                    elif  color_circulo2 == CircleAm
                        color_circulo2 = BombAm
                elif color_circulo1 == BombAm:
                    color_circulo1 = CircleAm
                    if color_circulo2 == CircleAz
                        color_circulo2 = BombAz
                    elif  color_circulo2 == CircleRo
                        color_circulo2 = BombRo
                    elif  color_circulo2 == CircleVe
                        color_circulo2 = BombVe
                    elif  color_circulo2 == CircleAm
                        color_circulo2 = BombAm
         else:
            colision_detectada = False 
