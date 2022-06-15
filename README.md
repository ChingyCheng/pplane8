# pplane8
record my problems and solutions in pplane
rectify pplane8 on MATLAB R2016b
I have already solve this problem
You only need add 'Parents' in 
meload = uimenu('Parents',mefile,'label','Load a system ...',...
'callback','pplane8(''loadsyst'',''system'');',...
'pos',1);
Repeatedly change all this type of errors and it works
and when you use latest matlab
here is the problem you may meet:

'numb','off' -> remove all of these Key/Value pairs. Sometimes they are wrapped around a line end. So search for 'numb' and remove the 'numb','off' pair from each occurrence.
'call' -> 'CallBack'
'number' -> 'NumberTile'

if notice -> if ishghandle(notice)
if gstop -> if ishghandle(gstop)
if dud.notice & dud.noticeflag -> if ishghandle(dud.notice) & ishghandle(dud.noticeflag)

and use the latest
Phase Plane and Slope Field apps
   https://github.com/MathWorks-Teaching-Resources/Phase-Plane-and-Slope-Field

Copyright John C Polking, Rice University, original 2003. Updated by Hugh Harvey and George Williams, University of Bristol, 2016.
