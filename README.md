# 📊 Visualize Your Network Like Never Before!

![Project logo](https://github.com/SimpleMethod/Network-Visualization/blob/67c6305438f0fc64a07a159fbae1d89e81b03474/logo.png)

Welcome to the Network Visualization! This powerful tool allows you to create stunning, interactive network diagrams with ease. Whether you're mapping out complex IT infrastructures!.

### 🌟 Key Features

- **Dynamic Network Rendering**: Create beautiful, force-directed network graphs
- **Customizable Styling**: Tailor your diagram's appearance to your needs
- **Flexible Node Grouping**: Organize nodes into logical super-nodes
- **Intelligent Layout Options**: Position nodes and groups with precision
- **Traffic Flow Visualization**: See network loads at a glance with color-coded links
- **Interactive Elements**: Zoom, pan, and click for more details
- **Export Options**: Save your diagrams as SVG for further use

## 🚀 Quick Start

1. Clone the repository:
   ```
   git clone [https://github.com/yourusername/network-visualization-project](https://github.com/SimpleMethod/Network-Visualization)
   ```
2. Navigate to the project directory:
   ```
   cd network-visualization-project
   ```
3. Install dependencies:
   ```
   mvn install
   ```
4. Run the application:
   ```
   mvn spring-boot:run
   ```
5. Open your browser and go to `http://localhost:8081`

## 🛠 Usage

To generate a network diagram, send a POST request to `http://127.0.0.1:8081/api/diagram` with your network configuration in JSON format. Here's an example structure:

```json
{
  "config": {
    "fontSize": 13,
    "fontColor": "#000000",
    "fontType": "PLAIN",
    "backgroundColor": "#ffffff",
    "borderColor": "#000000",
    "nodeColor": "#ffffff",
    "colorStrategy": "RED_GREEN",
    "title": "Example diagram #1",
    "showTitle": true,
    "showLegend": true
  },
  "nodes": [
    {
      "id": "n1",
      "position": {
        "x": 390.0,
        "y": 425.0
      },
      "size": {
        "width": 30.0,
        "height": 30.0
      },
      "label": "#1"
    },
    {
      "id": "n2",
      "position": {
        "x": 440.0,
        "y": 425.0
      },
      "size": {
        "width": 30.0,
        "height": 30.0
      },
      "label": "#2"
    },
    {
      "id": "n3",
      "position": {
        "x": 490.0,
        "y": 425.0
      },
      "size": {
        "width": 30.0,
        "height": 30.0
      },
      "label": "#3"
    },
    {
      "id": "n4",
      "position": {
        "x": 125.0,
        "y": 85.0
      },
      "size": {
        "width": 30.0,
        "height": 30.0
      },
      "label": "#4"
    },
    {
      "id": "n5", 
      "position": {
        "x": 720.0,
        "y": 205.0
      },
      "size": {
        "width": 30.0,
        "height": 30.0
      },
      "label": "#5"
    },
    {
      "id": "n6",
      "position": {
        "x": 812.0,
        "y": 275.0
      },
      "size": {
        "width": 30.0,
        "height": 30.0
      },
      "label": "#6"
    },
    {
      "id": "n7",
      "position": {
        "x": 740.0,
        "y": 790.0
      },
      "size": {
        "width": 30.0,
        "height": 30.0
      },
      "label": "#7"
    },
    {
      "id": "n8",
      "position": {
        "x": 720.0,
        "y": 405.0
      },
      "size": {
        "width": 30.0,
        "height": 30.0
      },
      "label": "#8"
    },
    {
      "id": "n9",
      "position": {
        "x": 455.0,
        "y": 335.0 
      },
      "size": {
        "width": 30.0,
        "height": 30.0
      },
      "label": "#9"
    },
    {
      "id": "n10",
      "position": {
        "x": 455.0,
        "y": 335.0 
      },
      "size": {
        "width": 30.0,
        "height": 30.0
      },
      "label": "#10"
    },
    {
      "id": "n11",
      "position": {
        "x": 455.0,
        "y": 335.0 
      },
      "size": {
        "width": 30.0,
        "height": 30.0
      },
      "label": "#11"
    },
    {
      "id": "n12",
      "position": {
        "x": 455.0,
        "y": 335.0 
      },
      "size": {
        "width": 30.0,
        "height": 30.0
      },
      "label": "#12"
    },
    {
      "id": "n13",
      "position": {
        "x": 455.0,
        "y": 335.0 
      },
      "size": {
        "width": 30.0,
        "height": 30.0
      },
      "label": "#13"
    },
    {
      "id": "n14",
      "position": {
        "x": 455.0,
        "y": 335.0 
      },
      "size": {
        "width": 30.0,
        "height": 30.0
      },
      "label": "#14"
    },
    {
      "id": "sfp+12",
      "position": {
        "x": 455.0,
        "y": 335.0 
      },
      "size": {
        "width": 30.0,
        "height": 30.0
      },
      "label": "#15"
    },
    {
      "id": "n16",
      "position": {
        "x": 455.0,
        "y": 335.0 
      },
      "size": {
        "width": 30.0,
        "height": 30.0
      },
      "label": "#16"
    },
    {
      "id": "n17",
      "position": {
        "x": 455.0,
        "y": 335.0 
      },
      "size": {
        "width": 30.0,
        "height": 30.0
      },
      "label": "#17"
    },
    {
      "id": "n18",
      "position": {
        "x": 455.0,
        "y": 335.0 
      },
      "size": {
        "width": 30.0,
        "height": 30.0
      },
      "label": "#18"
    },
    {
      "id": "n19",
      "position": {
        "x": 455.0,
        "y": 335.0 
      },
      "size": {
        "width": 30.0,
        "height": 30.0
      },
      "label": "#19"
    }
  ],
  "superNodes": [
    {
      "id": "sn1",
      "position": {
        "x": 200.0,
        "y": 200.0
      },
      "label": "Super Node 1",
      "nodePositions": [
        {
          "nodeId": "n1",
          "position": "BOTTOM"
        },
        {
          "nodeId": "n2",
          "position": "BOTTOM"  
        },
        {
          "nodeId": "n3",
          "position": "TOP"
        },
        {
          "nodeId": "n4",
          "position": "BOTTOM"
        },
        {
          "nodeId": "n5",
          "position": "BOTTOM"
        },
        {
          "nodeId": "n6",
          "position": "BOTTOM"
        },
        {
          "nodeId": "n7",
          "position": "BOTTOM"
        },
        {
          "nodeId": "n8",
          "position": "BOTTOM"
        },
        {
          "nodeId": "n9",
          "position": "BOTTOM"
        },
        {
          "nodeId": "n10",
          "position": "BOTTOM"
        }
      ]
    },
    {
      "id": "sn2",
      "position": {
        "x": 100.0,
        "y": 400.0
      },
      "label": "Super Node 2",
      "nodePositions": [
        {
          "nodeId": "n11",
          "position": "RIGHT"
        },
         {
          "nodeId": "n12",
          "position": "LEFT"
        },
         {
          "nodeId": "n13",
          "position": "TOP"
        },
         {
          "nodeId": "n14",
          "position": "TOP"
        },
         {
          "nodeId": "sfp+12",
          "position": "TOP"
        }
      ]
    },
    {
      "id": "sn3",
      "position": {
        "x": 0.0,
        "y": 0.0
      },
      "label": "Super Node 3", 
      "nodePositions": [
        {
          "nodeId": "n16",
          "position": "BOTTOM"
        }
      ]
    },
    {
      "id": "sn4",
      "position": {
        "x": 500.0,
        "y": 400.0
      },
      "label": "Super Node 4",
      "nodePositions": [
        {
          "nodeId": "n17",
          "position": "LEFT" 
        },
          {
          "nodeId": "n18",
          "position": "LEFT" 
        },
          {
          "nodeId": "n19",
          "position": "LEFT" 
        }
      ]  
    }
  ],
  "links": [
    {
      "sourceNodeId": "n1",
      "targetNodeId": "n13",
      "rxTraffic": 60.0,
      "txTraffic": 30.0
    },
    {
      "sourceNodeId": "n11",  
      "targetNodeId": "n17",
      "rxTraffic": 50.0,
      "txTraffic": 30.0
    },
    {
      "sourceNodeId": "n11",
      "targetNodeId": "n19",
      "rxTraffic": 50.0,
      "txTraffic": 30.0
    },
    {
      "sourceNodeId": "n3",
      "targetNodeId": "n16",
      "rxTraffic": 20.0,
      "txTraffic": 90.0  
    },
       {
      "sourceNodeId": "n16",
      "targetNodeId": "n3",
      "rxTraffic": 90.0,
      "txTraffic": 32.0  
    },
    {
      "sourceNodeId": "n2",
      "targetNodeId": "sfp+12",
      "rxTraffic": 40.0,
      "txTraffic": 20.0
    },
    {
      "sourceNodeId": "n10",
      "targetNodeId": "sfp+12",
      "rxTraffic": 20.0,
      "txTraffic":34.0
    }
  ]
}
```

![example diagram](https://raw.githubusercontent.com/SimpleMethod/Network-Visualization/67c6305438f0fc64a07a159fbae1d89e81b03474/example.svg)

## 🎨 Customization Options

- **Color Palettes**: Choose from various color strategies for link traffic visualization
- **Font Styling**: Adjust font size, color, and style to match your preferences
- **Background and Border**: Set custom colors for diagram background and borders
- **Title and Legend**: Toggle visibility and customize the diagram title and legend

## 🧩 Node Grouping and Positioning

Organize your network elements with our powerful grouping feature:

- Create super-nodes to group related nodes
- Position nodes within super-nodes using TOP, BOTTOM, LEFT, or RIGHT alignments
- Flexible layout options for complex network structures

## 🔗 Link Visualization

- Color-coded links based on traffic load
- Bidirectional traffic representation
- Customizable thresholds for traffic categorization

## 🖼 Output

The API returns an SVG representation of your network diagram, which you can easily integrate into your applications or documentation.


## 📄 License

This project is licensed under the Apache-2.0 license - see the LICENSE for details.

## 📞 Support

If you encounter any problems or have any questions, please open an issue on this repository

---

Happy Networking! 🎉 Don't forget to star ⭐ this repo if you find it useful!
