### Generic Experiements



<table> 
    <tr> <th colspan=4>   Pod Delete  </th> </tr>
    <tr > <td> Litmus Lib  </td> 
        <td> kill_count == " " </td> 
         <td> kill_count == 2 </td>
         <td> kill_count == value > pod-list.size() </td>
    </tr> 
    <tr > <td> Powerfulseal Lib  </td> 
        <td> kill_count == " " </td> 
         <td> kill_count == 2 </td>
         <td> kill_count == value > pod-list.size() </td>
    </tr> 
    </table>
         
 <br> <hr> <br>  
 
  <table> 
    <tr> <th colspan=3>   Container Kill  </th> </tr>
    <tr > <td rowspan=2> target_container  </td> 
        <td> null string </td>
    </tr>
    <tr>
         <td> name of container </td>
    </tr>
         </table>
         
   <br> <hr> <br>  
   
   <table> 
    <tr> <th colspan=3> Pod Cpu Hog </tr>
    <tr > <td rowspan=2> target_container  </td> 
        <td> null string </td>
    </tr>
    <tr>
         <td> name of container </td>
    </tr>
         </table>
         
   <br> <hr> <br>  
 
  <table> 
    <tr> <th colspan=3> Cpu Hog  </th> </tr>
    <tr > <td rowspan=2> auxiliary appinfo </td> 
        <td> null string </td>
         </tr>
    <tr>
         <td> provided auxiliary appinfo </td>
    </tr>
         </table>
         
 <br> <hr> <br>  
 
  <table> 
    <tr> <th colspan=2> Disk Fill </th> </tr>
    <tr > <td rowspan=2> auxiliary appinfo </td> 
        <td> null string </td>
    </tr>
    <tr> 
         <td> provided auxiliary appinfo </td>
    </tr>
    
    
  <tr > <td rowspan=2> target container </td> 
        <td> null string </td>
    </tr>
    <tr> 
         <td> provided container name</td>
    </tr>
         </table>
         
  <br> <hr> <br>  
 
  <table> 
    <tr> <th colspan=2> pod network latency </th> </tr>
    <tr > <td rowspan=2> target container </td> 
        <td> null string </td>
    </tr>
    <tr> 
         <td> value of container </td>
    </tr>
         </table>
         
  <br> <hr> <br>  
  
  <table> 
    <tr> <th colspan=2> pod network loss </th> </tr>
    <tr > <td rowspan=2> target container </td> 
        <td> null string </td>
    </tr>
    <tr> 
         <td> value of container </td>
    </tr>
         </table>
         
  <br> <hr> <br>  
 
  <table> 
    <tr> <th colspan=2> pod network corruption</th> </tr>
    <tr > <td rowspan=2> target container </td> 
        <td> null string </td>
    </tr>
    <tr> 
         <td> value of container </td>
    </tr>
         </table>
         
   <br> <hr> <br>  
 
  <table> 
    <tr> <th colspan=2> Drain Node  </th> </tr>
    <tr > <td rowspan=2> auxiliary appinfo </td> 
        <td> null string </td>
    </tr>
    <tr> 
         <td> provided auxiliary appinfo </td>
    </tr>
         </table>
         
   <br> <hr> <br>  
 
  <table> 
    <tr> <th colspan=4> Diss Loss  </th> </tr>
    <tr > <td rowspan=4> platform </td> 
        <td rowspan=2> GKE </td>
        <td rowspan=2> Auxiliary appinfo </td>
         <td >  null string </td>
    </tr>
    <tr>
         <td > some value </td>
    </tr>
    <tr> 
         <td rowspan=2> AWS </td>
        <td rowspan=2> Auxiliary appinfo </td>
        <td > null string</td>
    </tr>
         <tr>
         <td > some value </td>
    </tr>
    
   </table>
         
    
   ### Openebs Experiements
    
   <br> <hr> <br>  
 
  <table> 
    <tr> <th colspan=3> Openebs-target-container-failure  </th> </tr>
    <tr > <td rowspan=3> Docker Runtime  </td> 
        <td> Auxiliary Appinfo as null string </td>
        <td> Auxiliary Appinfo with some value </td> 
    </tr>
    <tr>
         <td> Data Persistance= mysql</td>
        <td> Data Persistance=busybox </td> 
    </tr>
    <tr>
         <td> stg_class= cstor </td>
        <td> stg_class = jiva </td> 
    </tr>
    <tr > <td rowspan=3> Containerd Runtime  </td> 
        <td> Auxiliary Appinfo as null string </td>
        <td> Auxiliary Appinfo with some value </td> 
    </tr>
    <tr>
         <td> Data Persistance= mysql</td>
        <td> Data Persistance=busybox </td> 
    </tr>
    <tr>
         <td> stg_class= cstor </td>
        <td> stg_class = jiva </td> 
    </tr>
   </table>
