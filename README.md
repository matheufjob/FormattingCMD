# FormattingCMD
Formatando qualquer disco de armazenamento com o CMD
Code

diskpart
list disk
select disk (y)
clean
create partition primary
select disk 1
active
format fs=fat32 Quick
assign
exit
