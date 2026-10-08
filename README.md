import pygame
pygame.init()


screen = pygame.display.set_mode((600,600))
screen.fill((255,255,255))
pygame.display.update()


run=pygame.image.load("run.png")
CANDY=pygame.image.load("CANDY.jpg")
Sqaure=pygame.image.load("Sqaure.png")
sub=pygame.image.load("sub.png")


screen.blit(run,(150,100))
screen.blit(CANDY,(150,100))
screen.blit(Sqaure,(150,100))
screen.blit(sub,(150,100))






font=pygame.font.SysFont("Times New Roman",36)











