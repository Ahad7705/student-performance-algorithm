Start
Set totalMarks = 0
Set i = 1
While (i < n) do
    totalMarks = totalMarks + marks[i]
    i = i + 1
End While

average = totalMarks / n

If (average >= 50) then
    performanceLevel = "Satisfactory Performance"
Else
    performanceLevel = "Academic Support Required"
End If

Print ("Average Score: " + average)
Print ("Performance Status: " + performanceLevel)
End
