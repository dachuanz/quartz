#QuartzUtils
依赖jar quartz-2.2.1.jar
下载地址：[quartz](http://www.quartz-scheduler.org/)
<table class="table table-bordered table-striped table-condensed">
   <tr>
      <th>Expression </th>
      <th>Meaning</th>
   </tr>
   <tr>
      <td>0 0 12 * * ? </td>
      <td>Fire at 12pm (noon) every day</td>
   </tr>
   <tr>
      <td>0 15 10 ? * * </td>
      <td>Fire at 10:15am every day</td>
   </tr>
   <tr>
      <td>0 15 10 * * ? </td>
      <td>Fire at 10:15am every day</td>
   </tr>
   <tr>
      <td>0 15 10 * * ? * </td>
      <td>Fire at 10:15am every day</td>
   </tr>
   <tr>
      <td>0 15 10 * * ? 2005 </td>
      <td>Fire at 10:15am every day during the year 2005</td>
   </tr>
   <tr>
      <td>0 * 14 * * ? </td>
      <td>Fire every minute starting at 2pm and ending at 2:59pm, every day</td>
   </tr>
   <tr>
      <td>0 0/5 14 * * ? </td>
      <td>Fire every 5 minutes starting at 2pm and ending at 2:55pm, every day</td>
   </tr>
   <tr>
      <td>0 0/5 14,18 * * ? </td>
      <td>Fire every 5 minutes starting at 2pm and ending at 2:55pm, AND fire every 5 minutes starting at 6pm and ending at 6:55pm, every day</td>
   </tr>
   <tr>
      <td>0 0-5 14 * * ? </td>
      <td>Fire every minute starting at 2pm and ending at 2:05pm, every day</td>
   </tr>
   <tr>
      <td>0 10,44 14 ? 3 WED </td>
      <td>Fire at 2:10pm and at 2:44pm every Wednesday in the month of March.</td>
   </tr>
   <tr>
      <td>0 15 10 ? * MON-FRI </td>
      <td>Fire at 10:15am every Monday, Tuesday, Wednesday, Thursday and Friday</td>
   </tr>
   <tr>
      <td>0 15 10 15 * ? </td>
      <td>Fire at 10:15am on the 15th day of every month</td>
   </tr>
   <tr>
      <td>0 15 10 L * ? </td>
      <td>Fire at 10:15am on the last day of every month</td>
   </tr>
   <tr>
      <td>0 15 10 ? * 6L </td>
      <td>Fire at 10:15am on the last Friday of every month</td>
   </tr>
   <tr>
      <td>0 15 10 ? * 6L </td>
      <td>Fire at 10:15am on the last Friday of every month</td>
   </tr>
   <tr>
      <td>0 15 10 ? * 6L 2002-2005 </td>
      <td>Fire at 10:15am on every last friday of every month during the years 2002, 2003, 2004 and 2005</td>
   </tr>
   <tr>
      <td>0 15 10 ? * 6#3 </td>
      <td>Fire at 10:15am on the third Friday of every month</td>
   </tr>
   <tr>
      <td>0 0 12 1/5 * ? </td>
      <td>Fire at 12pm (noon) every 5 days every month, starting on the first day of the month.</td>
   </tr>
   <tr>
      <td>0 11 11 11 11 ? </td>
      <td>Fire every November 11th at 11:11am.</td>
   </tr>
</table>
