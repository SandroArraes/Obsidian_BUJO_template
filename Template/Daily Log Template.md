---
tags:
  - daily-log
  - <%moment(tp.file.title).format("YYYY-MM-DD")%>
  - <%moment(tp.file.title).format("gggg-[W]ww")%>
date: <%moment(tp.file.title).format("YYYY-MM-DD")%>
week: <%moment(tp.file.title).format("gggg-[W]ww") %>
read: 
write: 
log: 
workout: 
---

## Links
- [[5.Yearly Log/<%moment(tp.file.title).format("YYYY")%>|Yearly Log]]
- [[1.Daily Log/<%tp.date.now("YYYY-MM-DD", -1, tp.file.title, "YYYY-MM-DD")%>|<%tp.date.now("MM-DD", -1, tp.file.title, "YYYY-MM-DD")%>]]<--<%moment(tp.file.title).format("MM-DD")%>-->[[1.Daily Log/<%tp.date.now("YYYY-MM-DD", 1, tp.file.title, "YYYY-MM-DD")%>|<%tp.date.now("MM-DD", 1, tp.file.title, "YYYY-MM-DD")%>]]
- [[5.Yearly Log/<%moment(tp.file.title).format("YYYY")%>|<%moment(tp.file.title).format("YYYY")%>]]/[[3.Monthly Log/<%moment(tp.file.title).format("gggg-MM")%>|<%moment(tp.file.title).format("MM")%>]], [[2.Weekly Log/<%moment(tp.file.title).format("gggg-[W]ww") %>|W<%moment(tp.file.title).format("ww") %>]]
- [[4.Future log/FutureLog|Future Log]]

## 1. Principais Tarefas de Trabalho
- [ ] Tarefa 1

## 2. Eventos/Prazos/Compromissos
- [ ] Feliz Ano Novo!! Bem-vindo a 2025!!
<%*
const weekdayStr = tp.date.now("dddd", 0, tp.file.title, "YYYY-MM-DD");
if (weekdayStr === "Sunday" || weekdayStr === "星期日") {
	tR += "- [ ] Plan new week"
}
%>
<%*
const dateString = tp.file.title; // Assuming the file title is in "YYYY-MM-DD" format
const dateParts = dateString.split("-");
const year = parseInt(dateParts[0], 10);
const month = parseInt(dateParts[1], 10) - 1; // Month is 0-indexed
const day = parseInt(dateParts[2], 10);
const date = new Date(year, month, day);
const lastDayOfMonth = new Date(year, month + 1, 0).getDate(); // Get the last day of the month

if (day === lastDayOfMonth) {
	tR += "- [ ] Review the month";
}
%>

## 3. Notas e Ideias


## 4. Blocos de Tempo
### Planejamento do Dia
- [ ] 09:00 - 10:00 Manhã
- [ ] 10:00 - 11:00 Atividade profunda (Deep Work)
- [ ] 11:00 - 12:00 Treino
- [ ] 12:00 - 13:30 Atividade profunda (Deep Work)
- [ ] 13:30 - 15:00 Atividade profunda (Deep Work)
- [ ] 15:00 - 16:30 Atividade profunda (Deep Work)
- [ ] 16:30 - 17:30 Jantar
- [ ] 17:30 - 18:30 Descanso
- [ ] 18:30 - 19:30 Atividade leve
- [ ] 19:30 - 21:00 Atividade leve
- [ ] 21:00 - 22:00 Atividade leve
- [ ] 22:00 - 23:00 Atividade leve
- [ ] 23:00 - 24:00 Encerramento do dia

### Lembretes
- [ ] Planejar o próximo dia (<%* tR+="@"%><%tp.date.now("YYYY-MM-DD", 0, tp.file.title, "YYYY-MM-DD")%> 19:30)
- [ ] Revisar hoje (<%* tR+="@"%><%tp.date.now("YYYY-MM-DD", 0, tp.file.title, "YYYY-MM-DD")%> 22:30)


**Legenda de Formatos (Bullets)**
- Bullets Básicos
    - [ ] a fazer (- [ ])
    - [/] incompleto (feito pela metade) (- [/])
    - [x] feito (- [x])
    - [-] cancelado (- [-])
     - [I] ideia (- [I])
     - [*] Eventos (- [\*])
- Bullets de Migração
	 - [>] encaminhar (para o Registro Futuro) (- [>])
     - [<] reagendar (para o Registro Diário de amanhã) (- [<])
- Bullets Estendidos
    - [i] importante (- [i])
    - [u] alta prioridade/subir (- [u])
    - [d] baixa prioridade/descer (- [d])
    - ["] citação (- ["])
    - [l] localização (- [l])



