import React from "react";

class Dashboard extends Assessment {
  Dashboard = () => {
    return (
      <table>
        <thead>
          <tr>
            <th>Dashboard</th>
            <th>Inventory</th>
            <th>
              Orders
              <br />
              <i className="small">目</i>
            </th>
            <th>Shipping</th>
            <th>Channel</th>
            <th>lil</th>
            <th>Orders X</th>
            <th>
              Pending
              <br />
              Accepted
            </th>
            <th>
              E<br />
              Import
              <br />
              Orders
            </th>
            <th>
              AWB
              <br />
              Created
            </th>
            <th>
              Ready
              <br />
              to Ship
            </th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td>
              <i className="large fas fa-tachometer-alt"></i>
            </td>
            <td>
              <i className="large fas fa-box"></i>
            </td>
            <td>
              <i className="large fas fa-clipboard-list"></i>
            </td>
            <td>
              <i className="large fas fa-truck"></i>
            </td>
            <td>
              <i className="large fas fa-paper-plane"></i>
            </td>
            <td>
              <i className="large fas fa-paste"></i>
            </td>
            <td>
              <i className="large fas fa-exchange-alt"></i>
            </td>
            <td>
              <i className="large fas fa-calendar-times"></i>
            </td>
            <td>
              <i className="large fas fa-file-import"></i>
            </td>
            <td>
              <i className="large fas fa-file-medical"></i>
            </td>
            <td>
              <i className="large fas fa-check"></i>
            </td>
          </tr>

          <td></td>
          <td></td>
        </tbody>
        <td>
          <table>
            <thead>
              <tr>
                <th>Channel Y Order No</th>
                <th>Order Date</th>
                <th>Cancelled</th>
                <th>City</th>
                <th>Customer Name</th>
                <th>Order Value</th>
                <th>Status</th>
                <th>Operation</th>
              </tr>
            </thead>
            <tbody>
              <tr>
                <td>#TKN20203754</td>
                <td>2022-05-04</td>
                <td></td>
                <td>Lucknow</td>
                <td>Abhishek Dixit</td>
                <td>0.00</td>
                <td>Pending</td>
                <td>
                  <i className="small fas fa-caret-right"></i>
                </td>
              </tr>
              <tr>
                <td>#TKN20203753</td>
                <td>2022-05-04</td>
                <td></td>
                <td>Lucknow</td>
                <td>Abhishek Dixit</td>
                <td>0.00</td>
                <td>Pending</td>
                <td>
                  <i className="small fas fa-caret-right"></i>
                </td>
              </tr>
              <tr>
                <td>#TKN20203752</td>
                <td>2022-05-04</td>
                <td></td>
                <td>Lucknow</td>
                <td>Abhishek Dixit</td>
                <td>0.00</td>
                <td>Pending</td>
                <td>
                  <i className="small fas fa-caret-right"></i>
                </td>
              </tr>
            </tbody>
          </table>
        </td>
        <td></td>
      </table>
    );
  };
}
export default Dashboard;
