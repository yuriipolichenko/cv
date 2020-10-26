# cv
add resume


.tariff-plan--title .plan-border,
.tariff-plan--title .plan-border:visited {
  color: #484c55;
} /*Колір тексту кнопки*/
.tariff-plan--title .plan-border .current,
.tariff-plan--title .plan-border :hover {
  color: #49cbcd;
} /* Підсвічування тексту(Зміна його кольору) кнопки при наведенні на неї курсора */
.tariff-plan--title .plan-border:before,
.tariff-plan--title .plan-border:after {
  /*Підчеркування йде з середини, before і after показує напрямок вперед і назад */
  content: "";
  position: absolute; /* !Застосування підчеркування */
  height: 3px; /*Товщина лінії підчеркування*/
  right: 50%; /*Зміщення лінії підчеркування вправо*/
  bottom: -4px; /*Відстань від кнопки до підчеркування*/
  left: 50%;
  background: #49cbcd; /*Колір нижнього підчеркування*/
  transition: 0.8s; /*Час розкриття нижнього підчеркування (анімації)*/
}

.tariff-plan--title .plan-border:hover:before,
.tariff-plan--title .plan-border:before {
  left: 0;
}
.tariff-plan--title .plan-border:hover:after,
.tariff-plan--title .plan-border:after {
  right: 0;
}
